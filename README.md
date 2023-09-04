# ENPM-661-A-Star-Algorithm-for-a-Mobile-Robot
The A* algorithm is a widely used and efficient path planning algorithm in computer science and robotics.
It is employed to find the shortest path from a starting point to a goal point while traversing through a grid or graph of nodes with associated costs.
The cost function for every action is the combined costs of 
-> Cost from start node to current node 
-> Cost of action (step size of the robot, in our case)
-> Cost from current node to goal node

Action set - +30 degrees, +60 degrees, 0 degrees, -30 degrees, -60 degrees

Threshold distance around the goal - 1.5 units radius
![image](https://github.com/Rashmikapu/ENPM-661-A-Star-Algorithm-for-a-Mobile-Robot/assets/57038036/60362221-840a-4b89-9222-83fb5e42b7b5)

Following are the libraries required for running the code:

-> cv2

-> numpy

-> heapq

-> copy

-> math

User inputs :

--> Start coordinates

--> Goal coordinates

--> Clearance & Robot radius

--> Step size (1<= L <=10)

Sample test case, path after backtracking - 

![A_star_path](https://github.com/Rashmikapu/ENPM-661-A-Star-Algorithm-for-a-Mobile-Robot/assets/57038036/8bd3003f-6cae-410e-8647-d20495ed0203)

Nodes exploration - 

![ezgif com-video-to-gif](https://github.com/Rashmikapu/ENPM-661-A-Star-Algorithm-for-a-Mobile-Robot/assets/57038036/a2a1ddc3-4fd2-44da-9ac5-3001cdabc19a)

