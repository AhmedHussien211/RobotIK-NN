# RobotIK-NN 🤖🧠

Neural Network-Based Inverse Kinematics Solver for 6-DOF Robotic Arms

RobotIK-NN is a deep learning-based inverse kinematics solver designed for 6-DOF robotic manipulators.
The system predicts robot joint angles directly from the end-effector pose using a trained neural network built with TensorFlow.

The project also provides an interactive Tkinter GUI that allows users to manipulate the end-effector pose using sliders or manual input and instantly visualize the predicted joint angles.

This project demonstrates the application of neural networks in robotics, replacing traditional analytical or numerical inverse kinematics solvers with a data-driven approach.

## 🚀 Features

Neural Network model for Inverse Kinematics prediction

* Supports 6-DOF robotic arms

* Predicts joint angles from:

    Position: X, Y, Z

    Orientation: Roll, Pitch, Yaw

* Interactive Tkinter GUI

* Real-time slider controls

* Manual entry input fields

* Live joint angle updates

* Degree-based visualization

* Easy experimentation with different poses

## 🧠 How It Works

Traditional inverse kinematics methods rely on:

* Analytical equations

* Jacobian-based optimization

* Iterative numerical solvers

* RobotIK-NN replaces these methods with a trained neural network.

The model learns the mapping:

## (𝑋,𝑌,𝑍,𝑅𝑜𝑙𝑙,𝑃𝑖𝑡𝑐ℎ,𝑌𝑎𝑤)→(𝐽𝑜𝑖𝑛𝑡1,𝐽𝑜𝑖𝑛𝑡2,...,𝐽𝑜𝑖𝑛𝑡6)

This allows the robot to instantly predict joint configurations for a desired end-effector pose.

## 👨‍💻 Author

Ahmed Hussien

AI & Computer Vision Enthusiast

Engineering Student
