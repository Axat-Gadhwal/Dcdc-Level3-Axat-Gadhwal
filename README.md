# Dcdc-Level3-Axat-Gadhwal
This repo is created by Axat Gadhwal of grade 7th of APS Varanasi. 
<details>
  <summary>Day 1 - Inception of OpenSource EDA, OpenLANE and SKY130 PDK</summary>
 <details>
   <summary> Section 1 - How to talk to computers </summary>
  <details>
    <summary>Lecture 1 - Introduction to Microprocesser Chips</summary>
  
   #### Understanding the microchip from an Arduino board..


<img src="http://cdn-reichelt.de/bilder/web/xxl_ws/A300/ARDUINO_LEONARDO_02.png" alt="Arduino Leonardo" width="800" height="500">
<br>This is an arduino board and the square shaped thing in the right-downwards is called a chip.
<BR> We will be going to understand that square thing[chip].

#### Understanding the operating structure of The microprocesser chip through a diagram

<img src="https://raw.githubusercontent.com/Axat-Gadhwal/Dcdc-Level3-Axat-Gadhwal/refs/heads/main/Axat.png">

#### Structure of the microprocessor 

<img src="https://raw.githubusercontent.com/Axat-Gadhwal/Dcdc-Level3-Axat-Gadhwal/refs/heads/main/Microchip.png">

<img src="http://www10.edacafe.com/book/ASIC/Book/CH16/CH16-12.gif">
 
 ### As seen, a chip is actually inside a package, and is connected to various "PINS" or inputs/outputs. The locations of the pins and what they are are usually driven by the design of the PCB. A chip is also a very complex system, and has various components such as -:

<br> 1. Pads = Pads in microprocessor chips are small conductive areas on the chip's surface that serve as connection points for electrical signals, power, and ground. They facilitate communication between the microprocessor and external components, such as circuit boards and peripherals. Pads can be categorized as input, output, power, or ground pads, and their design is crucial for ensuring proper functionality and signal integrity.

<br> 2. Core = A core in a microprocessor is an individual processing unit that can execute instructions. Modern CPUs often have multiple cores (e.g., dual-core, quad-core) to enable parallel processing, improving multitasking and overall performance. Each core can handle its own tasks, allowing for more efficient computing.

<br> 3. Die = A die is a small block of semiconducting material, typically silicon, that contains the integrated circuits (ICs) of a microprocessor or other electronic components. It is the physical piece of silicon that is cut from a larger wafer during the manufacturing process.

### Macros and Foundry Ip's

<img src ="https://www.vlsisystemdesign.com/wp-content/uploads/2020/11/2.jpg">

<br>Macros and Foundry IPs are essential components in microprocessor design. Macros refer to fixed, reusable design elements, such as standard cells or functional blocks, that simplify the design process. Foundry IPs, on the other hand, are specialized intellectual property provided by semiconductor foundries, tailored for specific manufacturing processes, ensuring compatibility and performance in chip production.
</details>
<details>
  <summary>Lecture 2 - Introduction to Risc-V Architecture</summary>
 
  ### Risc-V Instruction Set Architecture(ISA)

  <img src="https://github.com/Axat-Gadhwal/images/blob/main/Risc-V%20Architecture.png?raw=true">

  <br> The meaning/explanation of the different things in this diagram are=-
  <br>1.Risc-V Architecture = It is basically a Clanguage program that consists all the codes. It is like the base[also called"neev" in Hindi] of risc-V.
  <br>2.Layout = It is the interior of the chip. Like codes but not in written forms!

  ##### Both of these processes give us the desired output...

  <br>But in-between this process, one thing is required as a medium. The medium for getting output is picorv 32a.
  ###### We can understand this by the following line "The Risc-V Architecture is a specification which gets implemented by the medium{picorv 32a} and gives us the output..
  
  #### RISC-V is an open standard instruction set architecture (ISA) based on reduced instruction set computing (RISC) principles. Key features include:

<br>Open Standard: Free to use and modify, promoting innovation.
<br>Simplicity: A small set of simple instructions for efficient execution.
<br>Modular Design: Base instruction set with optional extensions for customization.
<br>Scalability: Suitable for applications ranging from low-power embedded systems to high-performance computing.

 




</details>

<details>
  <summary>Lecture 3 - From software applications to Hardware</summary>

  #### In this document, We will learn about how software applications convert into Hardware...

  <br> When we click on the Software applications it gets converted into Binary digits because the computer only recognises two operations{0&1}.
  <br> Understanding this line through a diagram...

  <img src="https://private-user-images.githubusercontent.com/163879237/315209287-5e3fb422-7ca4-4657-b805-0d314d0deec7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzgyNTA2NjgsIm5iZiI6MTczODI1MDM2OCwicGF0aCI6Ii8xNjM4NzkyMzcvMzE1MjA5Mjg3LTVlM2ZiNDIyLTdjYTQtNDY1Ny1iODA1LTBkMzE0ZDBkZWVjNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMTMwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDEzMFQxNTE5MjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zNzY2YmQxMzI4ZDEyMzQwNDVkYzUzZmJmYzM3MmU0NTYzYzJlOGNiZWJmZjgzOGRmMmRiOTZmNjAxMmZmODU2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.MeGIVFFEr8aYzAmoOmrJ--o1pS-QRpU4kJuHj5vkozU">

##### Understanding components of this process
<br> 1. OPERATING SYSTEM => It is the main part of this process because all the things like compilers, assemblers, etc. are present in this. An operating system (OS) is system software that manages computer hardware and software resources, providing a stable environment for applications to run. It acts as an intermediary between users and the hardware, handling tasks like memory management, process scheduling, and device control. Examples include Windows, macOS, Linux, and Android.

<br> 2. COMPILERS => A compiler is a software tool that translates high-level programming languages into machine code or intermediate code that a computer can execute. It processes the code through stages like analysis and optimization, enabling developers to write complex applications while abstracting hardware details.

<br> 3. ASSEMBLER => An assembler is a software tool that converts assembly language into machine code, enabling a computer's processor to execute instructions. It translates human-readable mnemonics into binary instructions specific to a hardware architecture.
</details>


 </details>
 <details>
  <summary>Section 2 - Soc design and Openlane </summary>

   <details>
  <summary>Lecture 1 - Introduction to Components of Opensource Digital ASIC Design </summary>

### Digital ASIC Design

 Digital ASIC Design refers to the process of creating application-specific integrated circuits (ASICs) that perform digital functions. This design process involves several stages, from initial concept to final implementation, and is characterized by a focus on optimizing performance, power consumption, and area for specific applications.

 ASIC requires mainly three components for design. The three components are :-

 #### 1. RTL IPs (Register Transfer Level Intellectual Property)
<br>Description: Pre-designed and verified blocks of code that represent specific functionalities at the RTL level.
<br>Purpose: Accelerate the design process by providing reusable components, such as arithmetic units, memory controllers, and communication interfaces

#### 2. EDA Tools (Electronic Design Automation Tools)
<br>Description: Software tools used for various stages of the ASIC design process, including simulation, synthesis, place and route, and verification.

#### 3. PDKs (Process Design Kits)

<br>PDKs (Process Design Kits) are essential resources in the ASIC design process, providing the necessary information and tools for designing integrated circuits using a specific semiconductor manufacturing process.


### Inventors

Lynn Conway and Carver Mead are renowned for their groundbreaking work in very-large-scale integration (VLSI) chip design, which revolutionized the field starting in 1978. Their collaboration led to the development of simplified design methodologies that significantly advanced digital integrated circuit design and education. Their seminal textbook, Introduction to VLSI Systems, published in 1979, became a cornerstone in VLSI education, widely adopted by universities and instrumental in shaping the curriculum for electrical engineering and computer science students.

Conway and Mead's approach emphasized the separation of design from manufacturing, introducing simplified design rules and a timing model suitable for digital design, which allowed for more efficient and cost-effective chip production. Their innovations spurred the establishment of silicon foundries, enabling independent designers to fabricate custom chips, thus democratizing access to chip design and fostering a new wave of innovation in the semiconductor industry.

The impact of their work was profound, leading to the rapid growth of VLSI technology and the emergence of numerous startups in Silicon Valley during the 1980s, which contributed to the ongoing evolution of the microelectronics landscape.

#### Open Source Digital ASIC Design

<img src ="https://github.com/Axat-Gadhwal/images/blob/main/ASIC%20design.png?raw=true" width ="500" height ="500">

### What are PDKs?

<br> A Process Design Kit (PDK) is a comprehensive set of files and documentation that provides essential resources for designing integrated circuits tailored to a specific semiconductor manufacturing process. It includes design rules, device models, layout templates, and simulation tools, enabling ASIC designers to create manufacturable layouts while ensuring compliance with fabrication standards. PDKs serve as critical toolkits that bridge the gap between design and manufacturing, facilitating accurate predictions of circuit behavior and optimizing the overall design process for reliable and efficient production.

#### Open PDKs

<br> We will now continue about How to open PDks files. 

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(177).png?raw=true" width="500" height="500">

### Is 130nm old or not in use?

<br>The 130nm technology is considered old and is largely not in use for modern microprocessors. It was developed in the early 2000s, and while some niche applications may still utilize it, most current microprocessors are manufactured using much smaller process nodes, such as 7nm or 5nm. However, the 130nm process technology is still relevant in certain contexts:

<br>Educational Use: The SKY130 open-source Process Design Kit (PDK) utilizes the 130nm node, making it accessible for educational purposes and for new designers to learn chip design without the high costs associated with more advanced nodes.

<br>Mixed-Signal Applications: The 130nm CMOS technology is recognized as a reliable option for mixed-signal applications, which require both analog and digital components. Its maturity and existing intellectual property (IP) make it a practical choice for specific designs.

<br>Cost-Effectiveness: For low-volume production or specific applications where cutting-edge performance is not critical, the 130nm process can be more cost-effective compared to newer technologies.

<br>Legacy Systems: Some existing systems and devices still rely on 130nm technology, and manufacturers may continue to support these products to ensure compatibility and maintenance.

<br>In summary, while 130nm is considered an older technology in the context of cutting-edge microprocessors, it still finds utility in education, specific applications, and legacy systems.

### Is 130nm fast?

<br>130 nm chips are also not slow, as verified by intel and OSU-:

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(178).png?raw=true" height ="600" width = 700>


</details>

<details>
  <summary>Lecture 2 - Simplified RTL to GDSII Flow </summary>

  ### Simplified RTL to GDSII Flow

  ###### Things we are going to learn

  <img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(179).png?raw=true">

  <br> So lets begin...
  
##### The RTL to GDSII ( Register Transfer Level to Graphic Design System II) design process takes many steps, that are -:
<br> Synthesis = Synthesis is the process of converting high-level RTL (Register Transfer Level) code written in VHDL or Verilog into a gate-level netlist using EDA tools like Synopsys Design Compiler. It involves optimizing the design for area, speed, and power while mapping it to specific technology libraries. The output is a gate-level netlist that serves as the foundation for physical design and further verification steps.

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(180).png?raw=true">

<br>An RTL model, which stands for "Register Transfer Level" model, is a design abstraction used in digital circuit design to describe the behavior of a circuit by focusing on the flow of data between registers and the logical operations performed on that data:-

<img src="https://github.com/Axat-Gadhwal/images/blob/main/CellLayout.png?raw=true">

### Thank You. Because of the scarcity of time I was unable to do all assignments. So I am only doing Labs...
</details>



</details>

<details><summary>Section 3 -Labs- Getting familiar to Open Source EDA Tools</summary>
<details><summary>Lecture 1 - Openlane directory structure in detail</summary>

#### First we should launch the Vsd Squadron file in the Virtual box. This interface will come...

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(204).png?raw=true">

Then search for the terminal. Because we are going to type all commands in terminal.

##### So lets begin with Labs...

##### Type cd Desktop and then cd work/tools to change directory to Desktop/work/tools, as this is where all openlane files are stored.

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(182).png?raw=true">

##### Using ls -ltr to know all the contents stored in that file

###### ls -ltr lists files in long format, sorted by modification time, with the oldest files shown first.

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(183).png?raw=true">

#### In a VLSI design workshop, openlane_working_dir is the directory where all design files, synthesis results, place and route outputs, GDSII files, and logs are stored for a specific project, facilitating organization and management of the design process. We are firstly using the openlane_working_dir command and thence it will change the directory to Openlane...

##### Also using ls -ltr to see the contents in the Openlane directory

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(205).png?raw=true">

#### Now going with the PDKs file. We will be also using ls -ltr to see the contents and also exploring SKY 130a...

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(206).png?raw=true">

#### Now changing the directory to the SKY 130A
##### We will observe two files :- Libs.tech and Libs.ref{as seen in the figure below}
###### We will be going through both these files...

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(207).png?raw=true">

##### libs.tech is a crucial file in the design flow of integrated circuits, serving as a technology library that encapsulates essential information about the semiconductor process being utilized. This file plays a significant role in ensuring that designs are compatible with the specific characteristics and constraints of the technology.

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(208).png?raw=true">

##### libs.ref is a file commonly used in the context of VLSI design and integrated circuit development. It serves as a reference library that provides essential information about the standard cells and components available in a specific technology library.

###### Using cd ../ because it reverses the libs.tech directory and thus allowing us to change the directory to libs.ref

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(209).png?raw=true">

##### Now we will explore the "sky130_fd_sc_hd" directory
###### ALso exploring the contents

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(210).png?raw=true">

##### Now we will open "OPENLANE" directory..
###### Reversing back to the Openlane_working_dir file directory

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(211).png?raw=true">




</details>

<details><summary>Lecture 2 - Design Preparation step</summary>

  ### We will learn Design Preparation Step in this documentation...

##### To open Openlane, we can use the docker command using interactive. After invoking the docker command, the prompt changes to bash-4.2$, and then one must type ls -lrth, and subsequently ./flow.tcl -interactive package require openlane 0.9 retrives all the required information for openlane.

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(212).png?raw=true">

##### As we learnt earier about the implemenation of The Risc-V program. Using PicoRV32A to ensure the functionality of OpenLane involves leveraging this RISC-V core as a reference design throughout the ASIC design flow. It allows users to synthesize the RTL code, perform place and route, and validate the effectiveness of OpenLane's tools. This practical implementation serves as both a demonstration of the design flow and an educational resource for understanding VLSI design methodologies.

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(213).png?raw=true">

#### folder run Jan 31_18-12 is created inside the picorv32a directory which contains the command log files, results, and the reports dumped of the various tool. The folder will be only have the lef files generated by this design setup stage. The cell LEF files .lef and technology LEF files .tlef merge to generate merged.lef inside runs/tmp/, wherein a a folder with today's date will be created, inside which a tmp folder will have contents, and the merged.lef folder will contain the merged lef files.

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(214).png?raw=true">

#### Now we are going to run the runs/ tmp directory

##### Also we are going to see the contents

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(215).png?raw=true">


</details>

<details><summary>Lecture 3 - Review Files After Design Prep and Run Synthesis</summary>

## Coming back to the OPENLANE interactive

#### Opening the merged.lef file through the less command after design prep will give one a document as shown:

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(216).png?raw=true">

<details><summary>Lecture 5 - Steps to Charecterise Synthesis Results</summary>

#### after run synthesis ,printing statistics as shown below can be used to calculate flip-flops ratio

###### Flip flop ratio =no of DFFs/no of cells *100

<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(217).png?raw=true">
<img src="https://github.com/Axat-Gadhwal/images/blob/main/Screenshot%20(218).png?raw=true">

#### Flop rate = 8.943%

</details>

</details>

</details>

</details>  

<details><summary>Day 2 - Good vs Bad Floorplan and Introduction to Library Cells</summary>

<details><summary>Section 1 - Chip Floor Planning Considerations</summary>

<details><summary>Lecture 1 - Utilisation Factor and Aspect Ratio</summary>

### In this document we will learn about How to define width and height of core and die

#### The first step in physical design is to define the width and height of the core and die : Beginning with a very simple netlist, that can extrapolated later we will first draw a basic diagram in the form of symbols that we will later convert into physical designs. We will take each cell (gates, specific cell like flip flop) and give it a standard (although rough for now) dimensions. As an example here, each unit will be 1 unit x 1 unit - i.e. 1 sq. unit in size, and since there are 4 gates/flip-flops here, the total size of the silicon wafer will 4 sq. units.



</details>


</details>

</details>
