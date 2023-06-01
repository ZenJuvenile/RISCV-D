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

Chip floor planning considerations :

utilisation factor:

In physical design, the utilization factor is a measure of how effectively a given space or resource is being used. It provides insight into the efficiency and effectiveness of the design layout. The utilization factor is calculated by dividing the actual usage or occupancy of the space or resource by its maximum capacity or potential.

The formula for calculating the utilization factor is:

Utilization Factor = (Actual Usage / Maximum Capacity) * 100%

The actual usage represents the real or observed usage of the space or resource, while the maximum capacity is the total capacity or potential of the space or resource. By expressing the utilization factor as a percentage, it provides a clear indication of the extent to which the space or resource is being utilized.

The utilization factor is commonly used in various fields, such as manufacturing, transportation, and facility management. It helps decision-makers assess the efficiency of their designs and identify areas of improvement. By monitoring and optimizing the utilization factor, organizations can make informed decisions to enhance productivity, reduce waste, and improve overall operational performance.

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/a7c48a20-ee30-421a-b223-d77bfcd52620)

aspect ratio:

Aspect ratio refers to the proportional relationship between the width and height of a physical design or visual display. It is commonly used in various fields such as photography, filmmaking, and graphic design. The aspect ratio is typically expressed as a ratio of the width to the height, for example, 4:3 or 16:9.

The formula for calculating aspect ratio is relatively simple. It involves dividing the width by the height. Mathematically, it can be represented as follows:

Aspect Ratio = Width ÷ Height

For instance, if a design has a width of 800 pixels and a height of 600 pixels, the aspect ratio can be calculated as follows:

Aspect Ratio = 800 ÷ 600 = 1.33

This result indicates that the design has an aspect ratio of approximately 1.33:1, which is commonly referred to as 4:3.

Aspect ratio plays a crucial role in determining the visual composition and presentation of an image or video. Different aspect ratios have distinct effects on how the content is displayed. For example, a wider aspect ratio, such as 16:9, is commonly used in modern televisions and computer screens, providing a more cinematic and immersive viewing experience. On the other hand, a more square aspect ratio, such as 1:1, is often utilized in platforms like Instagram, which primarily focus on square imagery.

Designers and filmmakers carefully consider aspect ratio to ensure that their work is displayed optimally on various devices and platforms. By selecting an appropriate aspect ratio, they can control the framing, composition, and visual impact of their creations, ultimately enhancing the overall viewing experience.

ceoncept of precplaced cells:

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/6fb38475-0dcd-4830-86bc-43a65aa2e05f)

The concept of preplaced cells in physical design refers to the strategic placement of specific circuit modules or functional units within an integrated circuit (IC) layout during the design phase. These preplaced cells serve as fixed components that are positioned in predetermined locations, rather than being dynamically placed by the automated placement tools.

By incorporating preplaced cells, designers can exert greater control over critical circuit elements, ensuring their optimal positioning in terms of area utilization, performance, and power efficiency. These cells are typically used for crucial circuitry, such as clock generation, memory arrays, and high-speed interfaces.

The advantages of preplaced cells lie in their ability to enhance overall circuit performance and reduce power consumption. Since their locations are predetermined, designers can optimize their proximity to other key components, minimizing signal delays and improving timing closure. Additionally, preplaced cells facilitate better power distribution planning, enabling efficient power routing and reducing signal integrity issues.

Moreover, preplaced cells aid in design optimization by allowing for early floorplanning and power planning decisions. Designers can allocate space and define power distribution strategies based on the fixed positions of these cells, streamlining subsequent design steps.

However, the utilization of preplaced cells requires careful consideration. Their fixed placement may limit flexibility, making it challenging to accommodate changes or modifications during the design process. Furthermore, the manual placement of these cells adds an additional layer of complexity to the physical design flow.

In conclusion, the concept of preplaced cells in physical design offers significant advantages in terms of performance, power efficiency, and design optimization. It enables designers to strategically position critical circuit elements within an IC layout, resulting in improved functionality and enhanced overall design quality.

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/451ed49d-d603-4053-b84c-08a3c3e5a315)
De-coupling capacitor:

A decoupling capacitor is an essential component in the physical design of electronic circuits, particularly in integrated circuits (ICs) and printed circuit boards (PCBs). Its primary function is to stabilize the power supply voltage, reducing noise and maintaining a stable voltage level for sensitive components.

As electronic devices operate at high frequencies, sudden changes in current demand can cause voltage fluctuations and noise, leading to performance issues and signal degradation. Decoupling capacitors act as a buffer, providing a localized reservoir of charge that can quickly respond to these fluctuations. They essentially store electrical energy and release it when needed, effectively filtering out unwanted noise and voltage variations.

Decoupling capacitors are strategically placed close to power-hungry components, such as microprocessors, digital logic circuits, or high-speed memory modules, where they can absorb and supply instantaneous current demands. By reducing voltage fluctuations, they enhance the overall signal integrity and prevent potential problems like ground bounce, crosstalk, and electromagnetic interference.

The physical design of decoupling capacitors involves selecting the appropriate capacitance value, voltage rating, and package size based on the specific requirements of the circuit. The capacitance value should be sufficient to meet the current demands and the frequency range of the circuit. Higher capacitance values offer better noise suppression but may also introduce larger physical sizes and cost implications.

Moreover, the placement of decoupling capacitors is critical. They must be located as close as possible to the power and ground pins of the targeted components to minimize inductance and resistance in the supply path. This proximity ensures efficient energy transfer between the power supply and the components, reducing the impedance and maximizing the capacitor's effectiveness.

In summary, decoupling capacitors play a vital role in the physical design of electronic circuits by stabilizing power supply voltages, suppressing noise, and improving signal integrity. Their careful selection and placement contribute to the overall performance, reliability, and functionality of electronic devices.

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/9502c24f-ec37-4e2f-989c-597aee1488c7)

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/854fd35e-2253-48ac-8b53-e076e221c18a)

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/efa44ce9-2fb5-4dcd-81e7-ce9f12d9ec56)

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/89a72b2a-7fc7-46d1-a7e0-8a7ae64f67fd)

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/f1203587-5459-4f7e-a4f3-7a8d097e7190)

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/0f30997f-8548-4ec7-b910-0b5ba96e70f4)

Power planning:

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/6704fb03-f46b-48eb-8222-a0de4b2e8ff9)

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/45906872-0b8e-45d2-9a2d-3d4645c21b75)

![image](https://github.com/ZenJuvenile/RISCV-D/assets/92900305/5be8722d-fcb6-4caf-82cb-05548293b957)





