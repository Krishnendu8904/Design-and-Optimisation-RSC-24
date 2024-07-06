# TASK 1

This project isn't for the faint of heart. It's designed to test your mettle and push your skills in lunar rover design and simulation to the limit. 

Remember the Pragyan Rover launched along side the Chandrayan - 3 Mission?

<img src="https://github.com/Krishnendu8904/Design-and-Optimisation-RSC-24/blob/main/Media/pragyan.jpeg?raw=true" height = "450" width ="650">

## Challenge Brief:

Design and simulate a next-generation lunar rover capable of navigating uneven terrain, deploying a simple robotic arm for object manipulation, and housing a camera mount – all within the constraints of a virtual simulation environment. This rover should prioritize compactness for fitting within a 1.25 x 1.25 x1.25 meter box  during launch.

### Design Requirements:

* **Locomotion System:** Design a six-wheeled rover with independent motor control in your simulation software capable of traversing uneven surfaces. (Look up a Rocker-Bogie Mechanism)

<img src="https://github.com/Krishnendu8904/Design-and-Optimisation-RSC-24/blob/main/Media/rocker_bogie.png?raw=true" height = "300" width ="350">

* **A 2-Link Manipulator Arm:** Model a simple two-link robotic arm with a gripper end effector. The arm should fold and unfold within the simulated rover body for compactness.

* **Camera Mount:** Simulate a retractable camera mount that extends from the rover body for observation. Model a pan-tilt mechanism for the camera within the simulation to provide a wide range of virtual observation capabilities. Think of ways to protect the camera from dust.

<img src="https://github.com/Krishnendu8904/Design-and-Optimisation-RSC-24/blob/main/Media/camera_mount.jpeg?raw=true" height = "350" width ="350">

* **Power Source:** Design a folding mechanism for the solar panels to ensure compactness within the 1.25 cubic meter launch container during simulated launch.

* **Aesthetics (OPTIONAL):** Consider including a visually representative model of the virtual high-capacity batteries within the rover. This can add a touch of realism to your design. Think about designing a detailed virtual antenna and a central processing centre, etc.


### Deliverables

**Showcase your creation with these must-haves:**

* **Xacro Snippets Doc:** Explain your design with clear snippets and explanations for major components (chassis, wheels, etc.).
* **Fusion 360 File Link (Required):** Share your .FSL file (or equivalent) so others can explore your 3D model.
* **Video:** One to show the joint movements in Fusion360. Another one to show your rover spawning in an empty Gazebo world. 

**Remember:**

* **Focus:** Explain functionality, not the entire Xacro code.
* **Video Clarity:** Make your video informative and engaging.
* **Complete Picture:** All deliverables show your design, Xacro skills.


### Additional Resources:
* [Gazebo Tutorials](https://classic.gazebosim.org/tutorials)
* [Rocker-Bogie Suspension](https://en.wikipedia.org/wiki/Rocker-bogie)
* [Spawning Robot in Gazebo](http://wiki.ros.org/simulator_gazebo/Tutorials/SpawningObjectInSimulation)
