# ME401-Intoduction-to-R.O.S

#### Each branch on this repository is a different homework assignmnt  

This Branch Contains homework 1 & 2

# ME 401/5501–Robotics and Unmanned Systems HW_1  
### DUE January 29th

### Problem 1:

Complete the following ROS tutorials at http://wiki.ros.org/ROS/Tutorials

5. Understanding ROS Nodes
6. Understanding ROS Topics
7. Understanding ROS Services and Parameters

Save a screenshot of the Turtlebot simulator and show/print the screenshot.

### Problem 2:

Complete the following ROS tutorials at http://wiki.ros.org/ROS/Tutorials

12. Writing a Simple Publisher and Subscriber (Python)
13. Examining the Simple Publisher and Subscriber
15. Writing a Simple Service and Client (Python)
16. Examining the Simple Service and Client

Save a screenshot of the running code in tutorials 13 and 16, and print these screenshots to turn in.

# ME 401/5501–Robotics and Unmanned Systems HW_2  
### DUE February 5th

For this assignment you will be using ROS and Gazebo to simulate the Turtlebot3 Burger platform.  Help in loading the simulation can be found at http://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/. Make sure to go to the Gazebo part of the E-manual. When setting the model type, replace “${TB3_MODEL}” with “burger.”

### Problem 1:

Create a ROS node that makes the Turtlebot3 travel forward at 1.5 m/s for 5 seconds, then turns to the right at 0.15 rad/s for 2 seconds, then continues forward at 1.5 m/s for another 5 seconds before stopping. Log the position data, and velocity & angular velocity commands.

Create a subplot of the x & y position data, velocity & angular velocity commands versus time.Submit your Python code.

### Problem 2:

Create a ROS node that uses a feedback controller to control the heading of the Turtlebot3. Once you have adequately tuned the controller, collect the data (by writing to a log file) from a 90 degree step input. Create a plot of the desired and actual heading versus time.

What is the rise time, settling time, and percent overshoot of your controller?Submit your Python code.
