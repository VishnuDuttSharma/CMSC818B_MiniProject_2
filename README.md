# CMSC818B Mini Project 2

Paper to be covered: [Multi-Agent Coverage in Urban Environments](https://arxiv.org/pdf/2008.07436.pdf ). Authors: Shivang Patel, Senthil Hariharan, Pranav Dhulipala, Ming C Lin, Dinesh Manocha, Huan Xu, Michael Otte

**Short Summary**: We use the Multi-Agent Voronoi Cover Algorithm (Patel et al.) to solve perform path-plannign for Persistent Monitoring problem. [Link to the project](https://sites.google.com/view/miniproject2/home])


Team - Members:      
Jingxi Chen, Email: ianchen@terpmail.umd.edu  
Md Ishat E Rabban , Email:  ier@umd.edu           
Vishnu Dutt Sharma, Email: vishnuds@umd.edu      	  
Kulbir Singh Ahluwalia, Email: kulbir@umd.edu       



## How to use:

### Requirements
This project runs on Windows. The uploaded files require Visual Studio. We have used VS2019 for building it. 
However, you can install OpenGL and run with your choice of development environement as well. The CodeBlock project for this project is available [here](https://drive.google.com/file/d/1OWLsFMHUw359kQPCIbOT_pCztAVQi8Ag/view?usp=sharing)


### Steps

1. Voronoi Partitioning Algorithm
	1. Run `python3 voronoi.py 0 0 800 600 6`, where the argument represtent the rectangle boundary and teyh number of robots
2. Lawnmower Algorithm
	1. Copy the `voronoi.txt` file into `OpenGL_Visual_Studio/OpenGL/` folder
	2. Open the `OpenGL.sln` file in visual Studio
	3. Update Line 30 in `main.cpp` to ```#define inputfilename "voronoi.txt"```
	4. Build and Run the project


- For experiment on changing the number of UGVs: Generate voronoi.txt with the required number of robots (last argument)
- For experiment on changing the number of obstacles: Update Line 25 of main.cpp as desired
- For experiemnt on changing the visibility range of UGVs: Update line 26 of main.cpp as desired



