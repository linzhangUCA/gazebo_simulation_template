# Assignment 3 - Gazebo Simulation
Simulate the robot we've built in last semester in Gazebo. **Create a single ROS 2 package** to get all the things done. Or you can use this repository to get started:
```bash
cd ~/<your workspace>/src
git clone https://github.com/UCAEngineeringPhysics/assignment3-gazebo_simulation-<your github username>.git
cd ~/<your workspace>
colcon build
```

## Requirement
1. (50%) Create a valid URDF model and verify it in rviz.
2. (20%) Add collision and intertial perperties to your URDF file and verify in Gazebo.
3. (30%) Add differential drive plugin to your URDF file and verify it in Gazebo.  
Feel free to change colors for your links, attach mesh files to your link and build your own gazebo world.

### Note
- **Create only one package**
- A single launch file will do the job. You can use the one provided in this repository to get started, but you may need tinker it a little bit to fit your needs.
- Make sure you have all the supporting files (`<your model>.urdf`, `<your launch>.launch.py`, `<your rviz configuration>.rviz`, `<your world>.sdf`, `setup.py`) well organized and edited.

## Helpful Resources
- [URDF slides](https://drive.google.com/file/d/1DXEDGwWpaFWe_Xzx93hXRPVSj-GOh14P/view?usp=sharing)
- [Gazebo slides](https://drive.google.com/file/d/1aXFFRoTvQ1D2q7GJwJWFAl5qPwVjJcl6/view?usp=sharing)
