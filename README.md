# ELEVATOR-CONTROLLER-ARCHITECTURE

Introduction : Elevator controller module is the elevator’s brain. The controller is a series of relays, electronic sensors and a PLC (Programmable Logic Controller) that work together to help the elevator run smoothly and safely. All of the elevator’s functions and travel are controlled by this panel.

Objective : Design an elevator controller module capable moving up and down the floors while ensuring safety precautions.

Methodology : The design is based on the concept of finite state machines involving states like initialization, up, down and halt. The RTL code is also verified via testbench and timing diagrams.
Block diagram :
 
Technical Aspects : Designed an Elevator Controller using Verilog, by which we can manage specific floor selection as well as opening/closing doors using trigger sensors and timers. The design also includes safety precautionary measures like weight-overload and Emergency stop. 
