# About Repository:
RT2_assignment2 uses the second assignment of Research Track I as its base, however, instead of using python scripts to control the robot in the gazebo environemnt, a jupyter notebook is used instead. The notebook allows the user to input the desired X and Y coordinates, it will send these to the server and then display the robots trajectory on a graph as well as any already reached or cancelled goals. There is added functionality in widgets that display the robots current X and Y coordinate as well as a widget that connected to the laser scanner to display the distance from the closest object the robot it.

# How to Launch:
* Clone the repository using **git clone https://github.com/MackJackenna/RT2_assignment2.git**
* run **roscore&** 
* To run the simulation environment,
	* run **cd [ros_ws]/devel**
	* run **source setup.bash**
	* run **roslaunch assignment_2_2022 all_nodes.launch**
* To run the jupyter notebook,
	* run **jupyter notebook --allow-root --ip 0.0.0.0**
	* Navigate to *[ros_ws]/src/RT2_assignment2*
	* Open the file *RT2_Assignment2_Notebook.ipynb*

# Notebook Use:
Please run cells 1, 2 and 3 first. Then input your coordinates into the prompt boxes and confirm a goal. You are then able to run the remaining cells 4, 5, 6 and 7.


