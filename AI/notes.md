![Screenshot from 2022-04-29 15-37-53](https://user-images.githubusercontent.com/42698268/165925325-2f6af38f-0963-462e-b674-60e75a0cc832.png)


# Lecture - 01 - What is AI | Learn AI with real life e.g | can machine think
![Screenshot from 2022-04-29 09-31-53](https://user-images.githubusercontent.com/42698268/165884509-909ef288-03cf-459e-ad02-864c6f90b2ba.png)

![Screenshot from 2022-04-29 09-44-15](https://user-images.githubusercontent.com/42698268/165884514-3194e9a0-08e0-45bc-8a48-a68ebe3dcb69.png)

* **Reasoning** - MAchine should think something reasonable, something logical, e.g if we know that to qualify a particular exam the scoring marks is 40% and someone has scored 60% therefore we know that the person is going to qualify the exam, we want to think machines in a similar way so we want to put this reasoning/logic in the machine too.
* **Learning** - Just like humans who learn from their past experinces and behaviour, similarly we want machines to learn from their past experiences and use them for future references and can perform better in future situations.
* **Problem solving** - Whether we are doing game playing or any kind of mathematical computation then we need our computer to solve various types of problems, we want machines to think just like our mind and approach the particular problem just like humans do
* **Perception** - Just like humans, who percept things with their sense organs, similarly we want machines to percept things just like humans, for e.g tesla has made automatic cars and lets say that car is running and on a particular path it found a jam, so it will percept that and will take a decision and will notify other cars so that they will not come to that path.

# 1. Overview of AI

![Screenshot from 2022-04-29 10-07-29](https://user-images.githubusercontent.com/42698268/165885914-0b131ec3-ddab-4681-8db6-964c4e247b4d.png)
![Screenshot from 2022-04-29 10-07-43](https://user-images.githubusercontent.com/42698268/165885926-b043b30b-bfcc-416f-b968-efab3d9544a2.png)
![Screenshot from 2022-04-29 10-08-12](https://user-images.githubusercontent.com/42698268/165885929-b2752a88-211a-4f8f-bb8f-380ca7e60538.png)
![Screenshot from 2022-04-29 10-08-23](https://user-images.githubusercontent.com/42698268/165885933-055fbc3d-ddd9-474e-91cb-7496f0ea955c.png)

# 2. Problems of AI
![Screenshot from 2022-04-29 10-13-10](https://user-images.githubusercontent.com/42698268/165886462-18d243c7-1596-425d-b25a-d462866b48dd.png)

![Screenshot from 2022-04-29 10-14-45](https://user-images.githubusercontent.com/42698268/165886467-f1057bb6-5947-404b-895b-4dbbd83ce896.png)


![Screenshot from 2022-04-29 10-15-06](https://user-images.githubusercontent.com/42698268/165886497-d35dff92-2afd-421e-bf4f-c7559c0f8c37.png)

![Screenshot from 2022-04-29 10-15-22](https://user-images.githubusercontent.com/42698268/165886510-63edb712-9960-4830-b3db-4317253271d2.png)

# 3. AI techniques

![Screenshot from 2022-04-29 10-19-40](https://user-images.githubusercontent.com/42698268/165886836-ae0eadf5-fcdc-4f94-830a-33e71fa41e18.png)

![Screenshot from 2022-04-29 10-19-54](https://user-images.githubusercontent.com/42698268/165886840-f8c9ddfd-17c6-41d3-a621-7285de35664e.png)

![Screenshot from 2022-04-29 10-20-04](https://user-images.githubusercontent.com/42698268/165886886-44e00a10-867e-483f-8848-c1932458882d.png)

![Screenshot from 2022-04-29 10-20-16](https://user-images.githubusercontent.com/42698268/165886893-c60accc9-1f1f-485c-906d-604f74603a9b.png)

# 4. Defining the problem as state space search


![Screenshot from 2022-04-29 10-40-02](https://user-images.githubusercontent.com/42698268/165888264-1d0c457b-0951-4bc9-aebf-7027d693eaa7.png)

![Screenshot from 2022-04-29 10-40-11](https://user-images.githubusercontent.com/42698268/165888272-a9b95f3a-315c-49e8-a0b9-0458acefd705.png)

![Screenshot from 2022-04-29 10-40-20](https://user-images.githubusercontent.com/42698268/165888276-ba55ac12-6679-4fd0-9277-e1d294ab7b99.png)


![Screenshot from 2022-04-29 10-48-57](https://user-images.githubusercontent.com/42698268/165888841-7001e612-d4b8-4692-b62e-5c040d3850e4.png)

# Lecture - 03 - What is State Space Search | Introduction to problem solving in AI
* State space search means the number of states in which the problem can go, we know that when we are solving a problem we can't go directly to goal state from start state, there would be intermediatory states through which you have to go to reach the goal state
* All these set of states are used as representation
* In AI we talk about how to represent the state precisely
* If we have represented it precisely than we can analyze it properly
* So to represent the problem precisely and to represent the problem in all set of states, then we use the state space searching
* **S** - Here S is total number of states, S contains {Start state, Intermediatory states, Goal state)
* **A** - A is set of actions, i.e all possible actions


![Screenshot from 2022-04-29 11-19-53](https://user-images.githubusercontent.com/42698268/165892105-00c321f6-e3fb-4ec0-b0a1-1dfc60fa59e3.png)


* Let us take an example where we are given a 3x3 matrix which is the start state and another 3x3 matrix which is a goal state, we have to reach the goal state by choosing actions, All possible actions means, here in this example we can move our empty space towards up, down, left or right, therefore you should know about the legal and illegal moves, you can't take actions for illegal moves
* Now the last is **cost**, which can be distance, time or money or anything based on problem 
* So the benefits of state space search is, we are defining everything precisely, the agent is analyzing properly that how we can reach each of the state
* Here in the process when the searching will take place, there would be two types of searching, uninformed and informed search
    * Uninformed search - Just like the name, the searching will be uninformed i.e it will go to all possible states, and it will be exponential search taking time = O(b^d), which is obvioulsy a lot, here b = breadth and d = depth, in the above example of 3x3 matrix the problem can grow upto (3^20) states, i.e more than 3.5 billion states
    * 

# 7. Problem characteristics


![Screenshot from 2022-04-29 11-41-27](https://user-images.githubusercontent.com/42698268/165893315-8c6bf282-d6ca-4720-a17f-d3570881c712.png)


![Screenshot from 2022-04-29 11-41-46](https://user-images.githubusercontent.com/42698268/165893342-3ff6f18b-7d94-4507-8899-9e515354035b.png)



![Screenshot from 2022-04-29 11-41-56](https://user-images.githubusercontent.com/42698268/165893351-c9f38558-073a-42e3-b50b-b00a187bc300.png)


![Screenshot from 2022-04-29 11-42-04](https://user-images.githubusercontent.com/42698268/165893361-fe2edb15-9453-49b9-8238-34d48c8b370d.png)



![Screenshot from 2022-04-29 11-42-17](https://user-images.githubusercontent.com/42698268/165893368-f3ff8b35-8d9a-4281-a788-41c06268807e.png)


![Screenshot from 2022-04-29 11-42-48](https://user-images.githubusercontent.com/42698268/165893373-58cc3fe3-c1f7-4cc8-b281-8c4f801ce815.png)


![Screenshot from 2022-04-29 11-43-08](https://user-images.githubusercontent.com/42698268/165893385-a7557045-c512-46f2-83e0-d41ec53a1fb3.png)


![Screenshot from 2022-04-29 11-43-18](https://user-images.githubusercontent.com/42698268/165893396-a50faf73-48da-47a0-af9d-8205476f499f.png)

# 8. Tic - Tac - Toe Game


![Screenshot from 2022-04-29 11-47-49](https://user-images.githubusercontent.com/42698268/165893948-fb74f90e-da9e-4902-a413-2be870cf2af6.png)


![Screenshot from 2022-04-29 11-48-10](https://user-images.githubusercontent.com/42698268/165893956-c87429d6-c266-43be-b4ca-d6743ef38bce.png)


![Screenshot from 2022-04-29 11-48-22](https://user-images.githubusercontent.com/42698268/165893967-e05d899d-447f-4fe6-9cc3-36acf2e18b8d.png)


![Screenshot from 2022-04-29 11-48-38](https://user-images.githubusercontent.com/42698268/165893992-36a93c65-1465-4ff3-99ea-cbfef8146430.png)



![Screenshot from 2022-04-29 11-48-53](https://user-images.githubusercontent.com/42698268/165894000-3d1be100-4aad-4920-a399-0d3de75156ec.png)



![Screenshot from 2022-04-29 11-49-03](https://user-images.githubusercontent.com/42698268/165894006-ffc7f55a-0280-48e4-8c16-af21d907934d.png)

# MODULE 2

![Screenshot from 2022-04-29 15-38-01](https://user-images.githubusercontent.com/42698268/165925404-ddc52ba2-f165-4f33-9b20-6054c4716312.png)

# 1. Solving Problems by searching

Whenever the agent is confronted by a problem, its first action is seeking a solution is its knowledge system. This is known as the search for the solution in the knowledge base. Another attempt can be to search for a solution by going into different states. The search of the agent stops in the state when the agent reaches the goal state.

There are many approaches for searching a particular goal state from all the states that the agent can be in.

There are many search algorithms which are followed by an agent for solving the problems by searching. Some of them are:

* Random search
* Breadth-first search
* Depth-first search
* Best-First search(Heuristic search)
* A* search


* **Random search**:
In this search technique, an agent just keeps checking any random state for being it the goal state. This is not an effective way to search the solution because, in this search, each node can be searched again and again, there is no fixed path followed, problems like infinite searching can be faced.

# Lectur - 04 - Uninformed vs informed search



![Screenshot from 2022-04-29 12-43-41](https://user-images.githubusercontent.com/42698268/165900681-9948d437-09ad-4b3b-a243-3fb6fa36b33f.png)

* Uninformed searching is also called brute force method or blind searching
* In uninformed search, we do a brute force operation and try to operate on all possible solutions
* Taking the example of travelling salesman problem, we do (n-1)! searches
* Uninformed search gurantees that it will give you optimal solution, but in informed search it is not gurantee that you will get an optimal solution
* In informed searching we use Heuristic(anumaan) method, we use heuristic method in those cases only where their is exponential growth in time, which is also called NP or non polynomial problem, so to solve the problem in polynomial time, we use heuristic method



![Screenshot from 2022-04-29 15-36-16](https://user-images.githubusercontent.com/42698268/165925108-6bcf99e2-aa95-48b4-bf18-e02ad18dc0a0.png)


![Screenshot from 2022-04-29 15-36-25](https://user-images.githubusercontent.com/42698268/165925109-e10d4add-acb7-45d6-a453-501ae322fd62.png)

# 1. Depth First search, Breadth First search and other searching algorithms

```
Some important points
* DFS is incomplete as it is possbile that it will get stuck in loop and will not give an answer while BFS is complete algorithm, so it will always give answer and that would be optimal

* BFS will always give optimal solution, while this is not true in the case of dfs, it is possible that the solution given by dfs is more costly then the optimal one

*

```

![Screenshot from 2022-04-29 15-41-28](https://user-images.githubusercontent.com/42698268/165926460-cea43861-6625-4143-b700-5f87527bbf27.png)


![Screenshot from 2022-04-29 15-41-37](https://user-images.githubusercontent.com/42698268/165926462-3e745370-b552-4372-9c98-e24f3cef0611.png)

![Screenshot from 2022-04-29 15-41-57](https://user-images.githubusercontent.com/42698268/165926466-27006fa8-a4b0-41d6-9bf3-b52734192794.png)

![Screenshot from 2022-04-30 12-20-50](https://user-images.githubusercontent.com/42698268/166095329-40053499-9488-40ef-83fa-449ad73c1b82.png)



![Screenshot from 2022-04-29 15-42-16](https://user-images.githubusercontent.com/42698268/165926461-143da6db-1641-4c17-b4b1-365ab39feb68.png)

![Screenshot from 2022-04-29 15-42-35](https://user-images.githubusercontent.com/42698268/165926471-9eb0b028-3574-4279-a019-28117bb32d6a.png)

![Screenshot from 2022-04-30 12-30-00](https://user-images.githubusercontent.com/42698268/166095574-aefe44a7-8e24-4f14-b977-94d90750c9a9.png)


![Screenshot from 2022-04-29 15-42-54](https://user-images.githubusercontent.com/42698268/165926489-affdc14b-8b4d-4733-876f-e4e9f0a5dd46.png)



![Screenshot from 2022-04-29 15-43-10](https://user-images.githubusercontent.com/42698268/165926497-d895b746-2f70-4523-a23a-2eec62f9ab46.png)


![Screenshot from 2022-04-29 15-43-19](https://user-images.githubusercontent.com/42698268/165926504-25173a40-90cf-4ac4-8d6e-5b0e4404bdc3.png)



![Screenshot from 2022-04-29 15-43-35](https://user-images.githubusercontent.com/42698268/165926509-909cc4a8-49b4-4fce-a6c7-f5315e5c8f94.png)

![Screenshot from 2022-04-29 15-43-45](https://user-images.githubusercontent.com/42698268/165926519-cbc29aa7-f8ca-48d3-a4cf-5f613fe124e0.png)


![Screenshot from 2022-04-29 15-43-53](https://user-images.githubusercontent.com/42698268/165926532-0cc62fa6-1f36-4a7d-9067-6cdef664a7a4.png)

![Screenshot from 2022-04-29 15-44-06](https://user-images.githubusercontent.com/42698268/165926538-171188a8-d4fd-477e-bcd7-dfe2f2351577.png)





![Screenshot from 2022-04-29 15-44-24](https://user-images.githubusercontent.com/42698268/165926545-02993b32-8900-49c1-a72a-a12bfe2b5650.png)



![Screenshot from 2022-04-29 15-44-35](https://user-images.githubusercontent.com/42698268/165926558-675b5b44-069f-4fbd-9076-aa5f14924b1a.png)


![Screenshot from 2022-04-29 15-44-43](https://user-images.githubusercontent.com/42698268/165926561-f738c0c5-f481-4f37-999d-e82a6465739e.png)





![Screenshot from 2022-04-29 15-44-58](https://user-images.githubusercontent.com/42698268/165926565-d5cffaca-eb8e-4849-a4a9-6230633b8b1b.png)


# 2. Depth limited search and Bidirectional search

![Screenshot from 2022-04-29 15-51-08](https://user-images.githubusercontent.com/42698268/165927702-f537fd1e-3e73-4088-91c1-8f5b44443b16.png)

![Screenshot from 2022-04-29 15-51-17](https://user-images.githubusercontent.com/42698268/165927707-f1baf39a-24df-486a-ac19-4a81d0026940.png)


![Screenshot from 2022-04-29 15-51-37](https://user-images.githubusercontent.com/42698268/165927716-694102cd-2e26-40e1-86c9-5551bd70532f.png)



![Screenshot from 2022-04-29 15-51-50](https://user-images.githubusercontent.com/42698268/165927723-0bf60359-6228-4e4b-8711-61f0001b72f3.png)



![Screenshot from 2022-04-29 15-52-01](https://user-images.githubusercontent.com/42698268/165927730-640ac406-2334-4cd5-9c22-287a795bf7b1.png)


![Screenshot from 2022-04-29 15-52-15](https://user-images.githubusercontent.com/42698268/165927738-ade8f0c6-67dd-490c-a055-cfe74882a5bb.png)


![Screenshot from 2022-04-29 15-52-25](https://user-images.githubusercontent.com/42698268/165927745-26cdfc2d-66d6-4445-ac6b-36fe8d024525.png)

![Screenshot from 2022-04-29 15-52-52](https://user-images.githubusercontent.com/42698268/165927764-eb422966-e1dc-40af-87ae-45e7413aed4d.png)



![Screenshot from 2022-04-29 15-53-02](https://user-images.githubusercontent.com/42698268/165927773-932ac7d5-ac3e-496c-b860-6adcf4355c5e.png)


![Screenshot from 2022-04-29 15-53-15](https://user-images.githubusercontent.com/42698268/165927791-aa7ab92f-3973-498e-b958-1caa7ac9d9a6.png)


![Screenshot from 2022-04-29 15-53-29](https://user-images.githubusercontent.com/42698268/165927812-104b250e-bb81-40c5-8b7d-b3d036951cb8.png)



![Screenshot from 2022-04-29 15-53-55](https://user-images.githubusercontent.com/42698268/165927819-a3903e14-d6a8-423d-a9c8-ee673e8175fa.png)



![Screenshot from 2022-04-29 15-54-10](https://user-images.githubusercontent.com/42698268/165927833-1eade5a6-c0cb-408d-9a78-cffed4c28aff.png)



![Screenshot from 2022-04-29 15-54-19](https://user-images.githubusercontent.com/42698268/165927840-efbab388-b370-4eec-b2ab-3650229cf2db.png)

![Screenshot from 2022-04-29 15-54-28](https://user-images.githubusercontent.com/42698268/165927849-26ab01c5-aef7-4a97-9aca-beb9ffb07556.png)

# 3. Best First search

![Screenshot from 2022-04-29 16-07-36](https://user-images.githubusercontent.com/42698268/165929405-8c87a35c-6a8a-40c2-b261-7114af38bf77.png)


![Screenshot from 2022-04-30 11-44-30](https://user-images.githubusercontent.com/42698268/166094220-3917920c-1f6c-4eb7-ad33-5a048c5e578d.png)

![Screenshot from 2022-04-30 11-44-46](https://user-images.githubusercontent.com/42698268/166094222-c4f507fb-1802-45cd-b98d-7b2fc18f41f2.png)


![Screenshot from 2022-04-30 11-45-17](https://user-images.githubusercontent.com/42698268/166094227-90c0749a-c2fe-4e02-b015-9310d472eac9.png)

![Screenshot from 2022-04-30 11-45-34](https://user-images.githubusercontent.com/42698268/166094232-1bea5f48-3470-448b-8e71-c7e2358bf66f.png)












