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
# Lectur - 04 - Uninformed vs informed search
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


































