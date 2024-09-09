# QUADRUPED
Design and data for quadruped robot along with description and manual.

## Table of Contents
- Introduction
- Components
- Description
- Slicing Scheme
- Assembly Scheme

## Introduction
- The repository containes cad .f3d files native to fusion 360, as well as stl files. Some of the files are in .iges format that may contain multiple components joined together with specified constraints and appropriate degrees of freedom.
- .stl files can be used for viewing as well as can be used as raw cad file to slice into G-codes for 3D printing. Assembly and joining scheme is described and will be mentioned in this file also.
- Model is to be 3D printed completely all the components needed tob be 3D printed are mentioned in the bill of components with number required.

## Components
- The actuator used in the model is "Orange OT5116M 6V 15kg.cm Digital Servo Motor" high torque servo motor.  
    Link to buy: https://robu.in/product/orange-ot5116m-6v-15kg-cm-digital-servo-motor/
- Other components are 3D printed bill of components is:  
          - body fe one x1          
          - body fe two x1          
          - body ma one x1          
          - body ma two x1          
          - hub left down x2          
          - hub left up x2          
          - hub right down x2          
          - hub right up x2          
          - leg_left x2          
          - leg_right x2          
          - rest_casing_lid x4          
          - thigh_right x4
- Electronic components required are:        
          - Single board computers (Arduino or Raspberri pi)        
          - jump wires        
          - Breadboard        
          - Li-ion Battery        

  ## Description
  - All the components needed to be 3D printed preferably according to the slicing scheme.
  - The model is optimised according to the actuator specified earlier (see the assembly file for the blueprint and assembly instructions)
  - One part (body) is too big to be printed in one go hence, is divided into two different components (namely body male and body female), male part have projections and female part have matching grooves (the printing error and clearance is taken into account according SLA printers (about 1.5 - 4 mm) and all the grooves and projections are optimised). These components are in turn divided into two more parts for easy manufacturing.
  -  
