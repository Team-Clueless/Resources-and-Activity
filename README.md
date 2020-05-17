# Resources
This includes resources and other aids used in this task. 
Also add them in the google sheet if you will (It also has the Sensors - Cost and Accuracy sheet):

[Google Sheet](https://docs.google.com/spreadsheets/d/1677pbPVrC0k_S-_Ag4LNA7e_MAPI6DYkt85SMPdUM4o/edit?usp=sharing)

Links
-----

#### Virat simulation files
https://drive.google.com/drive/folders/1z8NtWolK-N9I7Y1f9hneI6UDtDOa15_g?usp=sharing
#### Using Plugins For Sensors/Controller
http://gazebosim.org/tutorials?tut=ros_gzplugins
#### Steps to ROSify custom build robots
https://answers.ros.org/question/270089/how-to-implement-ros-in-my-custom-made-robot/
#### Connecting robot with ros using gazebo plugins
http://gazebosim.org/tutorials?tut=ros_gzplugins

------
# Current Project State

* Fixed errors in all three world files, collision bugs, xml syntax bugs etc
* Assembeled virat from meshes
* Added cameras(x2) and a Differential drive
* Added teleop package

# Major Tasks - for the whole team

- [x] Choosing the relevant files from the resources given.
- [x] Spawning a "dry model" of the bot without any sensors, plugins or such.
- [ ] Choosing the right sensors and plugins for the bot.
- [ ] Setting up object and lane detection models and integrating them with ROS.
- [ ] Setting up the navigation stack for the bot - the path-planners and localisation techniques.
- [ ] Finding ~or making~ a controller.  

- [ ] Going through the IGVC guide. 

## Some design reports for reference

[Bender](http://www.igvc.org/design/2019/12.pdf)


### Abhijit
- [x] Finish workspace setup

### Ankit

### Ashwin
- [x] created basic launch files for worlds, tweaked the igvc_basic.world a little to avoid the error
- [x] add bot model to launch file
- [x] teleop package complete

