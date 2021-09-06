# basic_amr

 Download the package inside catkin_ws/src. Then put the follow commands:

 ```
 cd
 cd .gazebo/models
 cp -r /home/user/catkin_ws/src/labyrinth .
 ```

 Then, you can simulate the robot in gazebo inside a labyrinth with the following command:

 ```
 roslaunch basic_amr_gazebo basic_amr_empty_world.launch
 ```

 Also, you can simulate the robot in gazebo inside a labyrinth with the following command:

 ```
 roslaunch basic_amr_gazebo basic_amr_labyrinth.launch
 ```

 <img src="https://github.com/ALxander19/basic_amr/blob/main/basic_amr_inside_labyrinth.png" width="300" height="400">
