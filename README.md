# Resources
This includes resources and other aids used in this task. 
Also add them in the google sheet if you will (It also has the Sensors - Cost and Accuracy sheet):

[Google Sheet](https://docs.google.com/spreadsheets/d/1677pbPVrC0k_S-_Ag4LNA7e_MAPI6DYkt85SMPdUM4o/edit?usp=sharing)

## Links

Go-to Tutorials
---------------

#### Using Plugins For Sensors/Controller
http://gazebosim.org/tutorials?tut=ros_gzplugins

#### Steps to ROSify custom build robots
https://answers.ros.org/question/270089/how-to-implement-ros-in-my-custom-made-robot/

#### Connecting robot with ros using gazebo plugins
http://gazebosim.org/tutorials?tut=ros_gzplugins

Collision detection and Path planning
-------------------------------------

#### A Research Paper on Collision detection and obstacle avoidance
https://upcommons.upc.edu/bitstream/handle/2117/120371/tfm-noelia-llamazares-lvarez.pdf?sequence=1&isAllowed=y

Controller
----------

#### Motion control algorithms for sensor equipped robots
http://www-personal.umich.edu/~ykoren/uploads/Motion_control_algorithms_for_sensor-equipped_robots.pdf

#### MPC Controller
https://github.com/Jeremy26/mpc-controller

#### Article on PID Control
https://medium.com/@jaems33/understanding-robot-motion-pid-control-8931899c31df

#### Lane keeping in autonomous driving with Model Predictive Control & PID
https://medium.com/@jonathan_hui/lane-keeping-in-autonomous-driving-with-model-predictive-control-50f06e989bc9

Lane Detection
--------------

#### Curvature of lane and offset from centre of lane
https://github.com/ftrang88/EC601-Fall2017-Seamless-Track-Detection/tree/master/Our_main_code

------
# Current Project State

* Fixed errors in all three world files, collision bugs, xml syntax bugs etc
* Assembeled virat from meshes
* Added cameras(x2) and a Differential drive
* Added teleop package
* Added lidar
* Added slam package for mapping surroundings

# Major Tasks - for the whole team

- [x] Choosing the relevant files from the resources given.
- [x] Spawning a "dry model" of the bot without any sensors, plugins or such.
- [ ] Choosing the right sensors and plugins for the bot.
- [ ] Setting up object and lane detection models and integrating them with ROS.
- [ ] Setting up the navigation stack for the bot - the path-planners and localisation techniques.
- [ ] Finding ~or making~ a controller.  

- [ ] Going through the IGVC guide. 

## Some design reports for reference

[Bender](http://www.igvc.org/design/2019/12.pdf)&nbsp;&nbsp;&nbsp;&nbsp;[Virat](http://www.igvc.org/design/2019/23.pdf)

### Abhijit
- [x] Finish workspace setup

### Ankit
- [x] created urdf file without sensors for dry sim
- [x] added laser sensor
### Ashwin
- [x] created basic launch files for worlds, tweaked the igvc_basic.world a little to avoid the error
- [x] add bot model to launch file
- [x] teleop package complete
- [x] make slam package

