3D Reconstruction for Robotic Manipulation

Project Overview
  This project involves implementing a 3D reconstruction system from 2D images and utilizing the generated 3D model for robotic manipulation tasks. The primary objectives are:
  •	Capture and process 2D images to reconstruct a 3D model.
  •	Integrate the 3D model into a robotic simulator.
  •	Implement grasping algorithms to enable object manipulation using a robotic arm.
  
Prerequisites
To run this project, ensure you have the following installed:
  •	Python 3.8
  •	OpenCV (for image processing)
  •	NumPy (for numerical operations)
  •	ROS-Noetic (Robot Operating System) and Gazebo (for simulation)
  •	Additional Python packages: matplotlib, scipy
  
How to Run the Project

Step 1: 3D Reconstruction
Download the 3D_reconstruction.py and input the command below in the terminal. Make sure you are in the correct workspace.
python3 <enter path to file>
Step 2: Set up the Virtual Environment for the Robot
Integrate the 3D model into the simulation environment. Make sure you are in the correct workspace.
roslaunch <your_config_file> demo. launch

Troubleshooting
  •	Command Not Found: Ensure all dependencies are installed. 
  •	Syntax Error: Make sure you replace <package_name> with the actual name of the package directory you want to navigate to.
  
Author
  •	Name: Giacomo Demetrio Masone
  •	Course: 7CCEMSAP Sensing & Perception
  •	Supervisor: Dr. Oya Celiktutan
  
Acknowledgements
  •	Utilized open-source libraries: OpenCV, ROS, MoveIT
  •	Special thanks to the course instructors for their guidance.
  
License
This project is for academic purposes as part of the 7CCEMSAP coursework. Unauthorized use or distribution is prohibited.

