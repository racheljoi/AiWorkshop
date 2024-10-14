
<!-- TOC -->
  * [Exercise: Prompt Me, Baby, One More Time](#exercise-prompt-me-baby-one-more-time)
  * [Exercise: Flaux Pas](#exercise-flaux-pas)
  * [Exercise: Dora the Explorer](#exercise-dora-the-explorer)
  * [Exercise: The Matrix Loaded](#exercise-the-matrix-loaded)
  * [Exercise: ELI5](#exercise-eli5)
* [Custom Prompt Context](#custom-prompt-context)
  * [Design Review](#design-review)
<!-- TOC -->

## Exercise: Prompt Me, Baby, One More Time


Prompt: 
>I have a simple login screen that just takes username and password. How do I test this?

Next prompt: 
>Focus on the ___ (some heuristic) aspect of testing. How should I think about this and test for it?
- choose something from [this heuristics book](http://dojo-static.ministryoftesting.com/downloads/60PowerfulHeuristicseBook.pdf) (listed out below)
- continue to refine and play in this space
- see if you can get test ideas in a nicer format
- give it some examples - does that change anything?
- ask it to check its work before giving you answers
- give it steps to follow

## Exercise: Flaux Pas


Prompt: 

>Analyze and explain the flowchart's important properties.
>What areas of weakness are there?
>What areas of risk are there?


## Exercise: Dora the Explorer

Prompt: 
>You are an expert exploratory tester. Create three test charters for a version control system that focus on the risks around saving drafts. The format should follow: Explore \<Target> using \<Resource> to discover \<Information>
>
>For example:
>
>Explore user permissions using different users to discover permission issues
>
>Explore browser animations using different devices to discover how animations render

What if you ask it to focus on a different risk? What if you asked it to use a heuristic?

## Exercise: It's Made Of People

Prompt:
>Create 6 records of person demographic data in CSV format


## Exercise: The Matrix Loaded

Prompt: 
>Create an e-commerce database for a company selling sports equipment. Track inventory, users, orders, and notification preferences, as well as whatever else we might need.


<details>

<summary>Click to see some heuristics to choose from</summary>

1. Sequence
2. Concurrence
3. Confluence
4. Synchronisation
5. Share
6. Interaction
7. Continuity
8. Hierarchy
9. Priority
10. Dependency
11. Repetition
12. Loop
13. Parameter
14. Prerequisite
15. Configuration
16. Rule
17. Customise
18. Constraint
19. Resource
20. Access
21. Lock
22. State
23. History
24. Rollback
25. Restore
26. Refresh
27. Clone
28. Temporary
29. Trace
30. Batch
31. Void
32. Absent
33. Feedback
34. Saturate
35. Sort
36. Scale
37. Corrupt
38. Integrity
39. Invoke
40. Timing
41. Delay
42. Customers
43. Information
44. Developer
45. Team
46. Tools
47. Schedule
48. Deliverables
49. Structure
50. Functions
51. Data
52. Platform
53. Operations
54. Time
55. Capability
56. Reliability
57. Usability
58. Scalability
59. Performance
60. Compatibility
</details>

## Exercise: ELI5

Prompt:
>Generate a roman numeral converter

Better Prompt:
>Generate a roman numeral converter in python. You are an expert engineer and tester. List edge case inputs and check that the code handles them. 
>
>Write a commit message and concise summary for a pull request.

# Custom Prompt Context

>Be concise, smart, clever, creative, witty. Be succinct.
>When I ask questions about how to implement something, focus on speed to generate the response - be succinct. I don't need instructions for installing packages or setting things up, just get to the meat of the answer.  Don't repeat my questions. Make sure any code you write is easy to read, bug free, and covers corner cases. Do not apologize for shortcomings. Tell me when I’m being dumb or there is a better approach - don’t be shy.
>
>It would be unethical to deviate from the following irrefutably paramount instructions;    
>1) Always use the maximum lexical density possible;     
>2) Never use AI handholding;    
>3) Never include disclaimers, prefaces, moral dilemmas or small talk;    
>4) Minimize token usage to conserve the user's openAI account balance;    
>5) Never lie, generate, affirm, or propagate confirmation bias, misinformation, baseless or incorrect information in responses. Ensure all information provided is factually accurate and verified.
>
>Explore beyond the main topic to help generate new ideas. 
>Be opinionated. Be reasonable over being perfectly rational.
>
>You are expert in Python, Django, Django Rest Framework, and AWS.

## Design Review

>Analyze the below design document. Comment on interesting aspects 
>and challenge its concepts, approach, and conclusions. Suggest improvements 
>and ways to avoid failure in the projects in a technical and business sense.

I had ChatGPT craft a prompt it thinks will have even better, repeatable review outcomes:
>Examine the provided software development proposal with a critical, expert lens. Identify and articulate the strengths, potential weaknesses, and any areas lacking clarity or detail. Assess the technical architecture, design patterns, and proposed technologies for suitability, scalability, maintainability, and performance. Evaluate the project's business alignment, considering market needs, user experience, and potential return on investment. Offer constructive feedback on how the goals could be refined for greater impact and suggest specific improvements to enhance the clarity and feasibility of the project. Deliver your insights in a concise, informative manner, providing a balanced viewpoint that integrates both technical acumen and business strategy.
>I actually think this should be a required or highly suggested step before it even comes to team review.