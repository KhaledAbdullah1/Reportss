# 1.Installation
## 1.1 Configure your Ubuntu repositories
Configure your Ubuntu repositories to allow "restricted," "universe," and "multiverse." You can follow the Ubuntu guide for instructions on doing this.
## 1.2 Setup your sources.list
Setup your computer to accept software from packages.ros.org.
## 1.3 Set up your keys
```
sudo apt install curl # if you haven't already installed curl
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
```
## 1.4 Installation
First, make sure your Debian package index is up-to-date:
```
sudo apt update
```
Now pick how much of ROS you would like to install.
Desktop-Full Install: (Recommended) : Everything in Desktop plus 2D/3D simulators and 2D/3D perception packages
```
sudo apt install ros-noetic-desktop-full
```
ROS-Base: (Bare Bones) ROS packaging, build, and communication libraries. No GUI tools.
```
sudo apt install ros-noetic-ros-base
```
There are even more packages available in ROS. You can always install a specific package directly.
```
sudo apt install ros-noetic-PACKAGE
```
e.g.
```
sudo apt install ros-noetic-slam-gmapping
```
To find available packages, see ROS Index or use:
```
apt search ros-noetic
```
## 1.5 Environment setup
You must source this script in every bash terminal you use ROS in.
```
source /opt/ros/noetic/setup.bash
```
It can be convenient to automatically source this script every time a new shell is launched. These commands will do that for you.
Bash
```
echo "source /opt/ros/noetic/setup.bash" >> ~/.bashrc
source ~/.bashrc
```
zsh
```
echo "source /opt/ros/noetic/setup.zsh" >> ~/.zshrc
source ~/.zshrc
```
## 1.6 Dependencies for building packages
Up to now you have installed what you need to run the core ROS packages. To create and manage your own ROS workspaces, there are various tools and requirements that are distributed separately. For example, rosinstall is a frequently used command-line tool that enables you to easily download many source trees for ROS packages with one command.

To install this tool and other dependencies for building ROS packages, run:
```
sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential
```
1.6.1 Initialize rosdep
Before you can use many ROS tools, you will need to initialize rosdep. rosdep enables you to easily install system dependencies for source you want to compile and is required to run some core components in ROS. If you have not yet installed rosdep, do so as follows.
```
sudo apt install python3-rosdep
```
With the following, you can initialize rosdep.
```
sudo rosdep init
rosdep update
```
# 2.Tutorials
Now, to test your installation, please proceed to the ROS Tutorials.
# 3.ROS One-line Installation
Check out this tutorial to install ROS Noetic using a single command.
# Now i will put the pic 
![image](https://user-images.githubusercontent.com/108229185/179981244-4ce554fc-56a9-4496-a5bf-f8ed249233d1.png)
![image](https://user-images.githubusercontent.com/108229185/179981349-5bd51c13-2753-4312-a7d7-3b90e477bb4a.png)
![image](https://user-images.githubusercontent.com/108229185/179981412-53689b18-b49e-46e7-96ac-227e6062bdca.png)
![image](https://user-images.githubusercontent.com/108229185/179981474-210fed95-e459-4f4e-8da2-65dde8f970e0.png)
![image](https://user-images.githubusercontent.com/108229185/179981548-c486b298-1797-4aca-9c95-045f6f58dd3b.png)
![image](https://user-images.githubusercontent.com/108229185/179981584-3b5d44bd-6b7f-4621-b2ae-c5b0ccf31240.png)
![image](https://user-images.githubusercontent.com/108229185/179981628-e6f6e0d1-dfa5-4946-8c18-4615cf7bab36.png)
![image](https://user-images.githubusercontent.com/108229185/179981693-20a89797-0335-4465-9e84-548ee1023bc0.png)
![image](https://user-images.githubusercontent.com/108229185/179981925-7d749a19-f8d7-4034-b39f-62bfe662dab5.png)
![image](https://user-images.githubusercontent.com/108229185/179982007-f8a79f58-4233-437e-a047-cd83de0a4235.png)
![image](https://user-images.githubusercontent.com/108229185/179982067-2a7d3c0e-a62a-442a-aaa0-5cec5d1f0fd5.png)
![image](https://user-images.githubusercontent.com/108229185/179982114-8070ef49-5026-4ef5-9d3c-364a910c1d4c.png)
![image](https://user-images.githubusercontent.com/108229185/179982211-a30cf333-78ab-4ca0-a908-19f514fb07f5.png)
![image](https://user-images.githubusercontent.com/108229185/179982323-43425c3a-8f3d-47c4-9a96-02e53daee7c9.png)
![image](https://user-images.githubusercontent.com/108229185/179982351-27b18a80-3ed7-4b6c-937a-71dd08aa895a.png)
![image](https://user-images.githubusercontent.com/108229185/179982388-82c476a6-d9a2-4319-9f9e-5d984b34c13d.png)
![image](https://user-images.githubusercontent.com/108229185/179982429-df8ee21f-4544-4de1-81f6-f5ac675eb152.png)
![image](https://user-images.githubusercontent.com/108229185/179982483-433a153d-b48e-4fa8-b12e-e4784675d2c4.png)
![image](https://user-images.githubusercontent.com/108229185/179982526-1de28f07-e8b0-4a81-9caf-6f8a4f5f1276.png)
![image](https://user-images.githubusercontent.com/108229185/179982574-048437a3-aac8-4dc0-835c-f9e8eb67c531.png)
![image](https://user-images.githubusercontent.com/108229185/179982613-dfd94c44-7889-42b9-b0d6-54272d33f94d.png)
