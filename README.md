# Embedded-system-Walking-machine

Code developed for "A. Marino, - Programming and construction of a scale walking machine. ".  
Master's student "Calabria University". 
For any questions or suggestions write to alexismarino0109@gmail.com


# Sumary.
The project entails developing a scale system designed to emulate the operations of an electric walking machine, which is fully based on Embedded systems programming. Its core functionality revolves around a conveyor belt capable of adjusting velocities per user specifications, a stepper motor for configuring the conveyor belt's inclination, and strategically positioned input/output interfaces that facilitate model control.

At the heart of this system is the microcontroller STM32F411RET6, featuring an ARM Cortex-M architecture meticulously suited for embedded devices characterized by low power consumption. This choice ensures optimal performance and efficiency in line with the project's embedded systems focus.

# Objectives   
the main objectives are:
•	Generate controllers that allow us to configurate the velocity 
•	Generate an analogue input to set up the inclination of conveyor belt 
•	Configurate a 16x2 Lcd to show instructions and values.
•	Configurate the DC gear motor and servo motor for the conveyor belt and inclination respectively  
•	Control the velocity of the conveyor belt with a controller 
•	Generate a code capable of follow the logic presented in fig.1.


# Prerequisites
- The code was created and tested on the Matlab/Simulink 2023a environment

# File description
The repository contains three files
1. **MAIN**: This Matlab file contains the configuration parameters of the program and shows the poles of the plant after control.
2. **CD_MOTORControl2**: This simulink file contains the complete simulation of the CNC machine with its reference generator.
3. **Report**: This contains the explanation of the complete process, the mathematical formulations, and the control configuration.


# Example to run the experiment  
**"CNC cutting machine"**
### Matlab/Simulink simulation 
1. Download the files. 
2. Run the Matlab file "**MAIN**".
3. Open and run the Simulink file "**CD_MOTORControl2**"
4. The XY Graph block should start to show the results  
![image](https://github.com/fercho-0109/CNC-2D-cutting-machine-Control/assets/40362695/fdf0f90a-b552-409e-ade6-690a95bdbeeb)



