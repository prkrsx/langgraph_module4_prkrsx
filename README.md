# Module 4: Building Your Assistant
# Lesson 1: Parallelization
1. Learned that we can customize the graph to fan out and in which allows us to Parallelize- for example, we can tell the agent to retreive documents at one end and search the web at another to return an answer, using parallel nodes and reducers.
2. Also learned that LangGraph has a default order which it follows when you use parallel nodes but you can set a custom order using reducers.
3. Made changes to the code by adding edges and nodes as well as tested Parallelization on Studio.
⠀

<img width="1468" height="884" alt="image" src="https://github.com/user-attachments/assets/658d5379-4474-4fa7-b9b5-e3570c06f7c8" />
fig 4.1.1: Custom Fan In and Out example by tweaking the code
⠀

<img width="1470" height="832" alt="image" src="https://github.com/user-attachments/assets/5ed4f326-41cf-4ddc-a704-518d6787f2b2" />
fig 4.1.2: Using Langsmith Studio to understand Parallelization

# Lesson 2: Sub-graphs
1. Learned how to integrate sub-graphs in a graph and pass information using over-lapping keys.
2. Tweaked the code by adding another node called synthesize_solution that combines their results into one and returns solution.
⠀

<img width="2940" height="1772" alt="image" src="https://github.com/user-attachments/assets/f9ed4d1d-afda-48bf-8071-ab0bfec11ca5" />
fig 4.2.1: Added a function called synthesize_solution to combine fa_summary and report and return a solution.
⠀

<img width="2940" height="1658" alt="image" src="https://github.com/user-attachments/assets/127f6604-4bbd-4d14-8305-279eb4fbbf13" />
fig 4.2.2: Easier readibility of Sub Graphs through LangSmith UI

# Lesson 3: Map-reduce
1. I learned about map-reduce operations where "Map" breaks down a task into smaller sub-tasks, and then process each of these sub-tasks parallely, whereas "Reduce" combines the results of all these sub-tasks.
2. Tweaked the code by changing the conversation from jokes to poems, where best poem is chosen.
<img width="2940" height="1664" alt="image" src="https://github.com/user-attachments/assets/b4847a3c-5417-40cc-b0d0-c3aeed34a440" />
fig 4.3.1: Final result of tweaking the code on UI
