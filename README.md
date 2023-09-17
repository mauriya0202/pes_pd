# VLSI PHYSICAL DESIGN
<details><summary>Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK</summary>
  
## How to talk to computers

+ Pads: They are like doors to inputs and outputs
+ Core: Digital logic
+ Die: Size of the entire chip
+ Foundry IPs
+ Foundry: Place where chips get manufactured
+ Macros: Digital Blocks
+ Instruction Set Architecture

- EDA Toold
- PDK Data
- RTL Designs

### Labwork

![image](https://github.com/mauriya0202/pes_pd/assets/112739882/c56c2556-72a7-4f65-aa93-3ae4c8172c80)
![image](https://github.com/mauriya0202/pes_pd/assets/112739882/ffbf4a46-334b-405a-808a-ace1aaaf10e8)


</details>


<details><summary>Sky130 Day 2 - Good floorplan vs bad floorplan and introduction to library cells</summary>

## Chip Floor planning considerations

+ Defining width and height of Core and Die: 100% utilization of core area, practically its about 60%
+ Aspect ratio
+ Utilization Factor

- Concept of preplaced cells
- Decoupling Capacitors
- Power Planning
- Pin placement and logical cell placement blockage

### Labwork

+ Steps to run floorplan using OpenLANE

![image](https://github.com/mauriya0202/pes_pd/assets/112739882/44e6269a-a9e4-4c41-8505-373fc748ad69)
![image](https://github.com/mauriya0202/pes_pd/assets/112739882/315bbc15-666c-417c-b9a7-1d412ece35cd)

![image](https://github.com/mauriya0202/pes_pd/assets/112739882/15c5d7d5-26e4-4d1d-af45-e7064ef2ec5a)

+ Running Placement on OpenLane
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/76558be1-a790-43a4-9dc8-a41de29f3327)

+ Slew low threshold
+ Slew high threshold

</details>


<details><summary>Sky130 Day 3 - Design library cell using Magic Layout and ngspice characterization</summary>

+ Note: DRC errors in magic will be highlighted with white dotted lines
+ post layout simulation


#### Labwork for CMOS invereter NgSPICE Simulation
![image](https://github.com/mauriya0202/pes_pd/assets/112739882/95b50b30-5e87-4694-9b0b-ecf909229f1f)

![image](https://github.com/mauriya0202/pes_pd/assets/112739882/51ff8c52-d1d2-4b77-ac2e-6ac793f606d7)

### Lab Work

![image](https://github.com/mauriya0202/pes_pd/assets/112739882/efc7dd24-893f-4248-9d46-e50cd18337ee)
![image](https://github.com/mauriya0202/pes_pd/assets/112739882/f04b0e19-3a78-4128-8261-0acee6eaeaf5)


+ To extract SPICE Netlist
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/528090dd-04d5-45ac-9249-e583aa8dd429)
+ SPICE File
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/2c9df05f-2d05-4271-ab9c-9f0ce6bd5f0f)
+ SPICE file after wrapper for simulation
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/f619146a-d631-459d-a8ff-9809a6ef2190)
+ ngspice
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/7b14d0d1-c22c-49f3-a2dc-acc75c4f6990)


</details>


<details><summary>Sky130 Day 4 - Pre-layout timing analysis and importance of good clock tree</summary>

+Inner boxed define the PR Boundary
+ tracks.info : Where PNR can route the metal layers
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/31be7819-d0c7-4568-96a9-5c952e14637e)
+ Ports should be at intersection of the horizontal and vertical tracks of any layer (eg li1 metal layer)
+ Grid info to track info
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/1006c1c3-a919-47b0-b08a-9fc7220940f4)
+ Magic Layout to LEF
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/49567cb3-493a-46f9-bd66-c0aa9728ed3e)
  ![image](https://github.com/mauriya0202/pes_pd/assets/112739882/852136ac-168b-4b10-b33e-e901d91d57c9)
+ Including Custom Cell in to OpenLane Flow




</details>
