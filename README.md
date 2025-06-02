# Traffic_Light_Simulation

## Project Overview  
Hey! This is my simple traffic light simulation project using Verilog. I made it as part of learning how to design digital circuits. The simulation shows how a traffic light changes from green to yellow to red at a single intersection.

## Features  
- Basic traffic light sequence: green → yellow → red  
- Timing for each light phase (fixed for now)-trying to make it better
-   
- Testbench included to simulate and check how it works

## Files in this Project  
- `traffic_light.v` — The main Verilog code that controls the traffic lights  
- `testbench.v` — A testbench to simulate and verify the traffic light behavior  
- `README.md` — This file, explaining the project and how to run it

## How to Run the Simulation  
If you want to try running the simulation yourself, here’s what you can do:  
```bash
# Clone this repo
git clone https://github.com/Abhinandanaa/Traffic_Light_Simulation.git

# Go into the project folder
cd Traffic_Light_Simulation

# Compile and simulate using a Verilog simulator like ModelSim or Vivado
vlog traffic_light.v testbench.v
vsim testbench
run -all
