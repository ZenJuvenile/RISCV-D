# RISCV-D
Welcome to the RISC-V Architecture-Based GitHub repository, a comprehensive collection of resources and tools dedicated to the open-source RISC-V instruction set architecture (ISA). This repository serves as a hub for developers, researchers, and enthusiasts interested in exploring, implementing, and contributing to the RISC-V ecosystem.


   ![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/3c3fa02d-f04c-4a00-bf5f-6fa48d8692af)

Basic terminologies to know about Asic chip:

package: In the realm of physical design, a package refers to the encapsulation or casing that houses electronic components, such as integrated circuits (ICs) or microchips. It provides a protective and functional environment for the delicate components, ensuring their proper operation and longevity. The package serves as a bridge between the internal circuitry and the external world, facilitating connections with other components, circuit boards, and systems. It also plays a vital role in dissipating heat generated during operation, maintaining electrical integrity, and enabling efficient signal transmission. The design of a package involves considerations of size, shape, material, thermal characteristics, and electrical properties to optimize performance and reliability.

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/6e2e5275-c001-4522-91f7-ca362a0b4438)


Pad: In physical design, a pad refers to a specific component or structure that serves as a connection point between an integrated circuit (IC) and the external world. Pads are crucial elements in the layout of ICs as they provide the interface for electrical signals to enter and exit the chip. These pads typically consist of metal layers and are designed to facilitate the transmission of signals, power, and ground connections. Pads are meticulously placed and designed to ensure reliable and efficient communication between the IC and the outside environment.

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/765c0f3e-0e6c-4c31-a7c1-4ce373358cef)

chip: In the realm of physical design, a chip refers to a highly integrated electronic device that houses various components necessary for the functioning of a computer or electronic system. It is a miniature form of a circuit that incorporates transistors, resistors, capacitors, and other elements on a single piece of semiconductor material, typically silicon. The physical design of a chip involves the intricate arrangement and interconnection of these components to ensure optimal performance, efficiency, and reliability. It encompasses tasks like layout planning, placement, routing, and verification to achieve the desired functionality and meet specific design constraints. Overall, the physical design of a chip plays a critical role in enabling the seamless operation of modern electronic devices.


![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/811fb542-ee29-4f8a-bff7-92b2861e4a51)

core: In physical design, the core refers to the central processing unit (CPU) of a microprocessor or a system-on-a-chip (SoC). It is the primary component responsible for executing instructions and performing calculations in a computer or electronic device. The core contains the arithmetic logic unit (ALU) and control unit, along with registers and caches for efficient data manipulation and storage. It is designed with multiple transistors and integrated circuits, enabling it to process data at high speeds. The core's architecture, clock speed, and number of cores greatly influence the overall performance and power efficiency of a processor or SoC.


![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/82422c65-6318-437c-bb0e-ba3d2b6552c2)


die: Die in physical design refers to a small, usually rectangular piece of a semiconductor wafer that contains integrated circuitry. It is a crucial component in the manufacturing process of microchips and serves as the foundation for individual electronic devices. The die comprises various interconnected components, such as transistors, resistors, capacitors, and interconnects, which are fabricated using advanced lithography techniques. These components work together to perform specific functions within a chip. The die is typically cut from a larger wafer and then packaged to protect it from external influences. Its compact size and intricate circuitry enable the creation of powerful and efficient electronic devices.

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/f979bc7e-fd93-431e-882b-f4ffe9c6870c)


IPs: In the context of physical design, IPs (Intellectual Properties) refer to pre-designed functional blocks or components that can be integrated into a larger system or integrated circuit. These IPs are designed to perform specific functions such as memory, processors, interfaces, or specialized functions. They are created to save time and effort in the design process by providing ready-to-use building blocks that can be easily customized and incorporated into the overall design. IPs play a crucial role in modern chip design, enabling efficient and cost-effective development of complex integrated circuits with reduced time-to-market.


What happens insde the hardware:

   ![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/c0eaa6de-e340-4c0e-9407-f12ecba1a9f0) 


The process from software application to hardware involves several stages that enable the execution of computer programs on physical computing devices.

Firstly, software developers design and code applications using programming languages and development tools. These applications are typically written in high-level languages such as Java, Python, or C++. The code consists of instructions and logic that define the behavior of the application.

Next, the software code goes through a compilation process. A compiler translates the high-level code into a lower-level representation called object code or machine code. This step ensures that the code is in a format that can be understood and executed by the hardware.

The compiled code is then packaged into an executable file or an installer, which contains all the necessary resources and dependencies required for the application to run. The installer may include libraries, frameworks, and other components needed by the software.

To run the application, the user or an automated process installs the software on a hardware device. This can be a personal computer, a smartphone, a server, or any other computing device capable of executing software.

The hardware device processes the instructions provided by the software. It uses the central processing unit (CPU), memory, storage, and other components to execute the code and perform the desired operations. The hardware interacts with input and output devices such as keyboards, mice, displays, and network interfaces to receive input from the user and present output.

Throughout this process, software and hardware work together to enable the execution and functionality of the application, allowing users to interact with and benefit from the software's capabilities.

Soc Design and OpenLANE:

  ![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/c30fc941-80d1-45c9-8286-0ee8a0ac74be)

Open-source digital ASIC (Application-Specific Integrated Circuit) design refers to the process of developing custom integrated circuits with a focus on openness, collaboration, and transparency. Unlike traditional ASIC design, which is often proprietary and closed, open-source ASIC design aims to provide accessible and reusable resources for designing and fabricating digital chips.

In an open-source digital ASIC design, the design files and related documentation are freely available to the public. This allows anyone to study, modify, and contribute to the design, fostering a collaborative and community-driven approach. The open-source philosophy promotes knowledge sharing, innovation, and the democratization of chip design.

Open-source digital ASIC design leverages various design tools, methodologies, and hardware description languages (HDLs) to create and optimize digital circuit designs. Popular open-source tools and frameworks, such as Qflow, OpenROAD, and SkyWater PDK, provide a comprehensive suite of tools for design entry, synthesis, place and route, and verification.

The advantages of open-source digital ASIC design include increased flexibility, customization, and cost-efficiency. It enables designers to tailor the chip's functionality to their specific needs, making it ideal for specialized applications. Additionally, the collaborative nature of open-source design facilitates faster development cycles and fosters innovation by leveraging the collective knowledge and expertise of the community.

Overall, open-source digital ASIC design empowers individuals, research institutions, and startups by providing access to cutting-edge chip design technologies and promoting collaboration and innovation in the field of digital integrated circuits.


RTL2GDS:

   ![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/619d28b2-ead3-4006-abab-3d6846f2f25e)



The RTL2GDS (Register Transfer Level to Graphic Data System) flow is a critical process in the design and manufacturing of integrated circuits (ICs). It involves transforming a high-level hardware description of a digital design, known as the register transfer level (RTL), into a physical layout ready for fabrication.

The flow begins with the RTL, which represents the behavior and functionality of the digital design at a higher level of abstraction. The RTL description is then subjected to various stages of synthesis, where it is optimized for power, area, and performance. During synthesis, the RTL is transformed into a gate-level netlist, which represents the design using logic gates and flip-flops.

Once the gate-level netlist is obtained, it undergoes a series of steps collectively known as the physical design phase. This phase includes steps such as floor planning, placement, and routing. Floor planning determines the optimal placement of different functional blocks on the chip, while placement involves assigning specific locations to individual cells within each block. Routing establishes the interconnections between the cells based on the available metal layers and routing resources.

After the physical design is complete, the final layout is obtained, which includes information about the exact locations of all the cells and the routing details. This layout is then verified using various checks, such as design rule checking (DRC) and electrical rule checking (ERC), to ensure that it meets the fabrication requirements and specifications.

The RTL2GDS flow is a complex and iterative process that requires expertise in digital design, synthesis, physical design, and verification. It plays a crucial role in the successful realization of digital ICs, enabling the translation of a functional design into a physical layout ready for fabrication.

Open source EDA tools:

OpenLane is an open-source flow for the complete RTL-to-GDSII digital design implementation process. It leverages several open-source tools and commands to automate various stages of the Electronic Design Automation (EDA) process. Here's a description of some essential OpenLane commands and open-source tools used in EDA on a Linux system:

yosys: Yosys is an open-source synthesis tool that reads RTL (Register Transfer Level) descriptions and performs logic synthesis to generate a gate-level netlist. It is used in OpenLane for the initial synthesis stage.

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/4e847260-ed92-4e4f-a54c-372cae2752d7)


abc: ABC (A System for Sequential Synthesis and Verification) is a sequential synthesis and verification tool that performs technology mapping, retiming, and various other optimizations on the gate-level netlist generated by Yosys.

OpenSTA: OpenSTA (Static Timing Analysis) is an open-source static timing analysis tool that analyzes the timing characteristics of the design. It is used to ensure that the circuit meets timing constraints and to identify potential timing violations.

Magic: Magic is a layout viewer and editor that allows designers to visualize and edit physical layouts. In OpenLane, Magic is used for floorplanning, placement, and routing steps.

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/1b15e379-45ab-446e-a7ef-35cbeb6eca3f)

Netgen: Netgen is a digital netlist comparison tool that verifies the correctness of the netlist generated by OpenLane. It compares the output netlist against a reference netlist to identify any discrepancies.

Fault: Fault is a tool used for automatic test pattern generation (ATPG) to create test vectors that can detect and diagnose faults in the digital design. It is used to generate test patterns for various types of faults, including stuck-at, bridging, and delay faults.

TritonRoute: TritonRoute is a detailed router used in the physical design phase. It takes the placed and optimized design from OpenLane and performs the routing, ensuring that the physical design meets the specified design rules.

OpenROAD: OpenROAD is a set of open-source tools that provide an integrated flow for digital ASIC (Application-Specific Integrated Circuit) design. It includes various components like OpenROAD App, OpenROAD Flow, and OpenROAD System that assist in different stages of the design process.

Klayout: Klayout is a layout viewer and editor primarily used for viewing and verifying the physical layout of the design. It supports GDSII and other layout formats and provides powerful visualization and analysis capabilities.

Skywater PDK: Skywater Process Design Kit (PDK) is an open-source process design kit that provides process-specific data, models, and rules required for the design implementation. It includes technology files, design rules, and device models specific to the Skywater foundry process.

These are just some of the commands and tools that are commonly used in the OpenLane flow and open-source EDA on a Linux system. OpenLane itself integrates these tools and commands to provide an automated and efficient RTL-to-GDSII design implementation flow.


