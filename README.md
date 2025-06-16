# IITISoC-25-IVR11 Swarm Robotics

Team Members

_**Team Member 1**:  [Mohit Naval](https://github.com/Mohit-Naval)_

_**Team Member 2**:  [Bhavy Ranka](https://github.com/Bhavy-Ranka)_

_**Team Member 3**:  [Abhinav Jain](https://github.com/AbhinavJain06)_


Mentors

_**Mentor 1**:  [Lavanya Bhatnagar](https://github.com/Lavanya-1133)_

_**Mentor 2**:  [Zaryan ](https://github.com/mentor2)_

_**Mentor 2**:  [Dishank J](https://github.com/mentor3)_

## Resources
For our PS we are reffering to 
- [GitHub Repo](https://github.com/YePeOn7/ros2_omni_robot_sim.git)
- [Humble Documentation](https://docs.ros.org/en/humble/index.html)
- [Gazebo Documentation](https://gazebosim.org/docs/fortress/getstarted/)


## Getting Started

### Prerequisites
- Install ROS2 Humble
- Install Gazebo for humble (Gazebo Fortress)
- Install Slamtoolbox for humble
```bash
sudo apt install ros-humble-slam-toolbox
```

### Let's get going
1. Clone the HUMBLE branch of [repo](https://github.com/YePeOn7/ros2_omni_robot_sim.git) in ros2_ws by-
```bash
git clone -b humble https://github.com/YePeOn7/ros2_omni_robot_sim.git
```
2. Follow along the steps mentioned in the Repo.


## Some helpful commands
- Command to check branch version you cloned
```bash
git status
git branch
```


## Troubleshooting some common errors
### Xacro
If you encounter a error stating, No such file or directory as 'xacro'. Then use the following command
```bash
sudo apt update
sudo apt install ros-humble-xacro
```

### ROS Gazebo Bridge not found
Error:
```bash
PackageNotFoundError: package 'ros_gz_bridge' not found
```
Soluiton:
```bash
sudo apt update
sudo apt install ros-humble-ros-gz-bridge
```
