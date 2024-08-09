# Robotic-Arm-Simulation
This repository contains the design and simulation of a robotic arm, developed using Autodesk Inventor and MATLAB/Simulink. The project includes detailed 3D models, engineering drawings, and a system integration framework for virtual testing and analysis.
# Key Features 
• 3D Modeling: Designed a robotic arm in Autodesk Inventor, with comprehensive 3D models and engineering drawings.

• System Integration: Imported the 3D model into MATLAB/Simulink to integrate with system-level simulations.

• Virtual Testing: Conducted simulations to evaluate the robotic arm’s kinematics, dynamics, and control algorithms.

• Performance Optimization: Fine-tuned the control algorithms to enhance the arm’s functionality and performance.

# Prerequisites

• Solidworks 2001Plus and higher, Autodesk Inventor 2009-2021, or PTC Creo 1.0-8.0: For viewing and modifying the 3D models and engineering drawings.

• MATLAB/Simulink: For running the simulations and system integration.

• Simulink 3D Animation Toolbox (optional): For enhanced visualization of the robotic arm in the simulation environment.

# Installing Simscape Multibody
• Simscape™ Multibody™ Link is a plugin that you can install on CAD applications to export assembly models to Simscape Multibody. Specifically, the plugin exports a CAD assembly model as an XML file and body geometry files that you can convert into Simscape Multibody models using the smimport function. The plugin supports:

## SolidWorks®

## Autodesk Inventor®

## PTC®Creo™

• Whichever you choose, for detailed setup instructions, follow this link:

https://www.mathworks.com/help/smlink/ug/installing-and-linking-simmechanics-link-software.html

# Assembly
• To see my parts, navigate to the models/ directory.

### Assemble the Parts:

• Open the .iam (assembly) file in Autodesk Inventor to start the assembly process.

• If the assembly file is not provided, start by opening each part file (.ipt) in Autodesk Inventor.

### Use the assembly environment in Inventor to:

• Constrain components (e.g., joints, screws, and motors) together to form the complete robotic arm.

• Apply the appropriate constraints (e.g., mate, insert, angle) to align and secure the parts.

# Exporting The Model Into Simulink/Simscape
• Depending on where you're exporting from, the instructions will be different.

### USING INVENTOR - Follow this link:

https://www.mathworks.com/help/smlink/ug/export-robot-assembly-from-autodesk-inventor-software.html

### USING SOLIDWORKs - Follow this link:

https://www.mathworks.com/help/smlink/ug/export-robot-assembly-from-solidworks-software.html

### USING PTC CREO - Follow this link: 

https://www.mathworks.com/help/smlink/ug/export-robot-assembly-from-proengineer-software.html

# Simulating

## Model Initialization:

• Open the Simulink model and ensure all required Simscape blocks are connected properly.
• Check the parameters for physical components like joints, motors, and link masses in the Simscape model.


## Run the Simulation:

• Configure the simulation parameters (e.g., start/stop time, solver options).
Run the simulation to analyze the robotic arm’s kinematics, dynamics, and control performance.

## Visualize Results:

• Use Simulink scopes and Simscape logging to visualize the simulation results, such as joint angles, velocities, and forces.

## Visualize the Simulation: 

• If using the Simulink 3D Animation Toolbox, open the VRML file in the visualization/ directory to see an enhanced 3D visualization of the robotic arm in action.

