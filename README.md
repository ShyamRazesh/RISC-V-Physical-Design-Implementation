# RISC-V-Physical-Design-Implementation
The RV32I Processor is designed to support all RV32I Base Integer Instructions (Total -39). It’s a  three-stage pipelined processor which executes 32-bit instructions in program order.

---------------------------------------------------------------------------------------------------------------
Tools 

1.DC and ICC2 tool for Synthesis and PnR
2.Prime Time and StarRC for the Signoff process

--------------------------------------------------------------------------------------------------------------
Technology

Synopsys 32nm

---------------------------------------------------------------------------------------------------------------
Description
1. The RV32I Processor is designed to support all RV32I Base Integer Instructions (Total -39). It’s a three-stage pipelined processor that executes 32-bit instructions in program order.
2. Pipelined Stage I - The instructions are fetched from memory.
3. Pipelined Stage II - The instructions are decoded and the control signals for all generated. Branches, jumps and stores are executed in advance in this stage units.
4. Pipelined Stage III - Executes complete instruction and writes back the resultsin the register file
-------------------------------------------------------------------------------------------------------------------
Responsibilities:
1. Synthesizing the RISC-V RTL and generate the Gate Level netlist using tool DC compiler.
2. Implementing floor planning, Placement and Routing processes on the netlist using ICC2 tool.
3. Implementing Clock tree Synthesis Performing Timing Analysis and achieve timing closure.
4. Perform DRC, ERC and LVS for signoff
5. Exporting the final GDS-II

------------------------------------------------------------------------------------------------------------------------
Objectives:
1. To understand how to come up with various file like .tcl, .sdc, .vew, .def, .tech, .v, .vcs, and various reference libraries required for the physical design process and how to source those files.
2. To understand how to do the process of synthesis, dft, floorplan, powerplan, placement, clock tree synthesis, routing and signoff.
3. To understand how to correlate all the above process and how to handle the errors occuring during the physical design.

 ---------------------------------------------------------------------------------------------------------------------
 RISC-V

 
RISC-V stands for reduced instruction set computer (RISC) five.
The number five refers to the number of generations of RISC
architecture that were developed at the University of California,
Berkeley since 1981.
RISC-V is an open-source instruction set architecture (ISA) used
for the development of custom processors targeting a variety of end
applications.
Unlike proprietary processor architectures, RISC-V is an open-source
instruction set architecture (ISA) used for the development of custom
processors targeting a variety of end applications. Originally developed
at the University of California, Berkeley, the RISC-V ISA is considered
the fifth generation of processors built on the concept of the reduced
instruction set computer (RISC). Due to its openness and its technical
merits, it has become very popular in recent years. The standard is now
managed by RISC-V International, which has more than 3,000 members and which reported that more than 10 billion chips containing
RISC-V cores had shipped by the end of 2022. Many implementations
of RISC-V are available, both as open-source cores and as commercial
IP products.

As an open-standard architecture, RISC-V is defined by member
companies of RISC-V International, the global nonprofit organization
behind the ISA. The intent is that through collaboration, the member
companies can contribute new avenues of processor innovation while
promoting new degrees of design freedom.
The royalty-free RISC-V ISA features a small core set of instructions
upon which all the design’s software runs. Its optional extensions allow
designers to tailor the architecture for a variety of different end markets.
Essentially, the RISC-V architecture allows designers to customize and
build their processor in a way that’s tailored to their target end
applications, so they can optimize the power, performance, and area
(PPA) for those applications. The RISC-V ISA also provides the
flexibility to pick and choose from available features, rather than having
to use the full feature set.
While the initial market adoption of RISC-V has been with embedded
applications and microcontrollers, the open-source architecture also
holds promise for high-performance computing and data centers.
The history of RISC-V
RISC-V began as a project at UC Berkeley to create an open-source
computer system based on RISC principles. It was initially designed
for academic use. The standard has evolved and is now managed by
RISC-V International.
The RISC-V International organization has moved its headquarters to
Switzerland to maintain neutrality for designers worldwide without any
government regulations.



