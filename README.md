BrickBlock-Pi
=============

BrickPi robot controlled with web-based Blockly IDE 
=============

(Ctrl-c, ctrl-v of my final presentation notes cuz I'm too lazy to type up anything legit.)
____________________________________________________________________________________________
**Section I:** General summary of the project<br>
		1. Usage of Blockly coding language to interface with BrickPi-enabled RaspberryPi brain to guide a robot through a maze<br>
**Section II:** Explain what BrickPi/RaspberryPi is<br>
		1. RaspberryPi: Single-board single-core computer the size of a credit card<br>
		2. BrickPi: Slide on board for the RaspberryPi that makes it compatible with Lego NXT/EV3 robotics parts<br>
**Section III:** Explain what Blockly is<br>
		1. Blockly: Google-developed graphical programming language based around using blocks to code<br>
**Section IV:** Hardware components of the project<br>
		1. Two NXT motors that were synced up using P control<br>
			A. Master motor (Port A)<br>
				-Independent motor<br>
			B. Slave motor (Port D)<br>
				-Motor that has its speed corrected to mirror the speed of the master motor<br>
			C. P control<br>
				-Control system where the correction in the speed of the slave motor is proportional to the size of the error<br> 
		2. "Brain" of the robot<br>
			A. RaspberryPi/BrickPi combination<br>
		3. Wi-Fi dongle<br>
			A. Allows for wireless communication between RaspberryPi/BrickPi and computer<br> 
**Section V:** Software components of the project<br>
		1. C<br>
			A. libwebsockets<br>
				a. C library that provides server and client APIs that allow for two way communication between robot and computer<br>
			B. RobotC<br>
				a. IDE aimed at students to allow programming and controllnig of NXT, VEX, RCX, and Arduino robots<br> 
		2. HTML/CSS<br>
			A. Used to code the website used to program and control the robot<br>
		3. Javascript<br>
			A. Provided framework for all the bricks used in the Blockly language and allowed us to create our own blocks<br>
		4. Blockly<br>
			A. Graphical computer language used as the main interactive feature of the project<br> 
**Section VI:** Application of BlockPi bot in real life<br>
		-Extremely simple to build and control<br>
			-Children can be introduced to coding early on
