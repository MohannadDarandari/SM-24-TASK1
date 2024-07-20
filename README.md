# SM-24-TASK1
 here we i will show you how to install Ros-1 on ubuntu 20.04 

Step1:
you need to download VirtualBox 


Step 2:
now you need to download ubuntu 20.04 

you can used this link to download it :
https://releases.ubuntu.com/20.04/




Step 3:
after you download the ubuntu 20.04 you need to open the Terminal on the ubuntu and start to write this lines:

1- sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

2-sudo apt install curl



3-curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -

4-sudo apt update

5-sudo apt install ros-noetic-desktop-full




6-echo "source /opt/ros/noetic/setup.bash"





roscore
