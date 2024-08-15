# Performance-Monitoring-Dashboard

This is an Performance-Monitoring-Dashboard using this Monitoring-Dashboard the user can 
view the performance/parameter of the different cpu rescoures at any where , at any place , on the 
simple browser access. it can view the various parameter of the compuer like cpu load , total memory , free memory,
no of the cores , os_type , chip name etc. can serach by the OS Type of the Different resource and the filter by the only 
offline resource

It have the three parts :<br>
1) nodeClient which will run on the resource and sends its data to the server <br>
2) server which takes the data from different nodeclient and send it to the vite/react Client<br>
3) react Client which display data to the users , by taking the data from the server<br>

for running the application do npm i in each folder and run nodeClient at its proper position
and run server (npm run start) and viteClient (npm run dev)

here i have use the : React , CSS , Node.js , mongodb , socket.io

The website image is given as :

![perf 31](https://github.com/user-attachments/assets/919cfe49-1353-42dc-a073-ae503c1e3cdc)


![perf 32](https://github.com/user-attachments/assets/78d85bed-c1f2-4c22-a27b-63c922f223ed)



I hope this dashBoard will we very useful for tracking the different cpu resources  
