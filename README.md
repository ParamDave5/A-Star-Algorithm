# Implementation of A* on a point robot
This repository contains code to find a path between the start node and the goal node for a point robot using A* algorithm.  

The action set for this project is:  
<img src = "https://github.com/ParamDave5/A-Star-Algorithm/blob/f680b078a5c81c63746995cd683041db01f72991/results/action_set.PNG">  
where, L represents the step size.  

The threshold distance to reach the goal node is 1.5 units without any constraint on the orientation.
## Required libraries:
1. NumPy
2. OpenCV
3. queue
4. math
5. matplotlib  

## Instructions to run the code:
```
python A_star.py
```
Program accepts step size as input. Below output is for step size of 5.
### Node exploration
![](https://github.com/ParamDave5/A-Star-Algorithm/blob/f680b078a5c81c63746995cd683041db01f72991/gif/A_star.gif)  

### Generated path
![](https://github.com/ParamDave5/A-Star-Algorithm/blob/f680b078a5c81c63746995cd683041db01f72991/results/path.png)



