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

