First, execute the following at database.build

create table error_logs (
  id bigint primary key generated always as identity,
  error_message text not null,
  error_code int,
  occurred_at timestamptz default now() not null,
  user_id bigint,
  ip_address inet,
  url text,
  http_method text,
  user_agent text,
  stack_trace text
);

create table users (
  id bigint primary key generated always as identity,
  username text not null,
  email text not null unique
);

alter table error_logs
add constraint fk_user foreign key (user_id) references users (id);

---

Next, import the users file found in this folder. And finally, import the error logs file found in this folder.
