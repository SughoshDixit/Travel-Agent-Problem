# Travel-Agent-Problem
AI solution to determine Optimal Path using DFS and RBFS
A businessman wants to establish his new branches in Middle East countries. He needs to travel from Turkey to Kuwait by flight. Create an algorithm to help him to reach the destination with optimal cost. The cost factor may be attributed by ticket price, time taken on a particular route which are depicted in the below map. Here ticket price in dollars and time taken to particular route is denoted in Hours. By using the information provided for each city. Use the following algorithm to solve the problem:
a) Depth First Search
b) Recursive Best First Search

![image](https://user-images.githubusercontent.com/29068709/180639585-612f9b61-a1ad-486d-ab4d-8fad44a77609.png)

Note 1:
1. Between every pair of states, parameters = (ticket_cost-TC, time expected-Hours) is
given for each edge.
2. Take linear combination of the relevant cost parameters for your cost design without the loss
of information. Time taken is considered twice as important related ticket cost.
3. You may design your own heuristic function and explain in your documentation
