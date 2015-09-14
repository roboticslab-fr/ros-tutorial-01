# ROS Tutorial 01

# Introduction to ROS
![ROS Hydro]
(http://prerelease.ros.org/static/images/hydro.png)

# Introduction
This tutorial is mainly inspired from the workshop of GDR Robotique @Montpellier – July 2013.
Special thanks to Stéphane Magnenat & Francis Colas – Autonomous Systems Lab. ETH Zurich

## References
ROS Wiki - http://wiki.ros.org/

ROS Tutorials - http://wiki.ros.org/ROS/Tutorials

Suggested Courses – Summer course on ROS Framework 2013 - http://mediawiki.isr.ist.utl.pt/wiki/Summer_course_on_ROS_framework_2013

Support - http://answers.ros.org

## Tips
###ROS Distribution version
ROS Hydro is the only distribution for TurtleBot2 development during Robotics Pojects

**!!! Always select HYDRO in tutorials or documentation on the ROS wiki !!!**

###Buildsystem
A buildsystem generates executable files from source files.
Catkin is the only buildsystem used for new development. 
(Unless you need to compile "oldfashioned" packages with rosbuild)

**!!! Always select catkin in tutorials or documentation on the ROS wiki !!!**

Consult the ROS Wiki for further information: http://wiki.ros.org/catkin_or_rosbuild

#ROS Configuration
We performed some settings on our Workstations and TurtleBot2 Netbooks.
Every workstations and netbooks are already configured with ROS HYDRO.
Workspaces are configured to have catkin and rosbuild working alongside.

More infos on catkin: http://wiki.ros.org/catkin/Tutorials

The workspaces are :
* for catkin ~/ros/hydro/catkin_ws
* for rosbuild ~/ros/hydro/hydro_workspace

After ROS installation, the last step is to configure the ROS environment. The **~/.bashrc** file has to be
configured by adding lines to run correctly ROS commands. These lines launch a script that sets
environment variables.

##To Do

###Study tutorial on ROS environment
**!!! ROS environment is already set on the computer: do not creat again a workspace !!!**
http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment

###Check environment variables that contain “ROS” value

	$ export | grep ROS
	
###Study the ~/.bashrc file
Edit the ~/.bashrc file

###Study documentation on environment variables
http://www.ros.org/wiki/ROS/EnvironmentVariables
(the first two sections in particular)

