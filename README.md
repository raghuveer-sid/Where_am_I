# RoboND_Where_Am_I
Udacity Robotics Software Engineer Nanodegree Term 2 Localization Project:

### Running the Scripts
Run the following commands below in separate terminals: 

``
cd /home/workspace/catkin_ws``    
``catkin_make``   
``source devel/setup.bash``

Launch the world in Gazebo and RViz:  
`` cd /home/workspace/catkin_ws/``  
``roslaunch udacity_bot udacity_world.launch``  
Launch the AMCL node for localization:  
``roslaunch udacity_bot amcl.launch``  
Launch Navigation stack  
``rosrun udacity_bot navigation_goal`` 
