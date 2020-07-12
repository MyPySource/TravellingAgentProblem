# TravellingAgentProblem
Travelling Agent Problem constraints with the capacity that agent can carry in one way. 

<h1>Problem and Solution</h1>
This Problem has multiple constraints to address<br>
1. The time window for deliveries is met.<br>
2. Orders from one area are neatly clubbed together for maximum efficiency.<br>
3. Each boy can carry a maximum of 8 units of medicines.<br>
Create a route plan for the agents (10 agents) for ensuring these deliveries are done on time and that the delivery agents are back to the store by 7 pm.
<br>
<br>
<b> Breaking down to solution</b><br>
1) Find 10 number of closest points cluster to assign 10 agent to deliver the medicine<br>
2) Find the distance from shop to each delivery points<br>
3) Also find distance matrix to understand possible route available<br>
4) Assign each clustor to each agent with minimum spanning tree<br>
5) create a dict object to show agent and its route taken<br>
<br>
To understand the problem better waysee real time geo-locations on map <br>
https://www.google.com/maps/d/edit?mid=1CARxJ5R62SSaZk-5tHufsk72Um3Q2Sji&usp=sharing
