# Table of Contents
- [Syllabus](#Syllabus)
- [Literature Reference](#Literature-Reference)
- [Open Source EDA Setup](#Open-Source-EDA-Setup)
- [Course Materials](#Class-Material)


# Syllabus
**MODULE-I** (Chapter 1 to 5 of Text Book 1([Kang03]) and for Stick Diagram Text Book 2 ([Weste11]) )
- **Introduction**: Historical Perspective, VLSI Design Methodologies, VLSI Design Flow,Design
Hierarchy, Concept of Regularity, Modularity and Locality.
- **Fabrication of MOSFETs**: Introduction, Fabrication Processes Flow – Basic Concepts,The
CMOS n-Well Process, Layout Design Rules, Stick Diagrams, Full-Customs MaskLayout
Design.
- **MOS Transistor**: The Metal Oxide Semiconductor (MOS) Structure, The MOS System under
External Bias, Structure and Operation of MOS Transistor (MOSFET), MOSFET CurrentVoltage Characteristics, MOSFET Scaling and Small-Geometry Effects, MOSFET Capacitance.
- **MOS Inverters**: Static Characteristics: Introduction, Resistive-Load Inverters, Inverters
with n-Type MOSFET Load, CMOS Inverter.

**MODULE-II** (Chapter 6 to 8 of Text Book 1([Kang03]))
- **MOS Inverters - Switching Characteristics and Interconnect Effects**: Introduction, Delay-Time Definition, Calculation of Delay-Times, Inverter Design with Delay Constraints, Switching Power Dissipation of CMOS Inverters.
- **Combinational MOS Logic Circuits**: Introduction, MOS Logic Circuit with Depletion NMOD Loads, CMOS Logic Circuits, Complex Logic Circuits, CMOS Transmission Gates (Pass Gates).
- **Sequential MOS Logic Circuits**: Introduction, Behaviour of Bistable elements, SR Latch Circuits, Clocked Latch and Flip-Flop Circuits, CMOS D-Latch and Edge-Triggerd Flip Flop.

**MODULE-III** (Chapter, 9 to 11 and 15 of Text Book 1)
- **Dynamic Logic Circuits**: Introduction, Basic Principle of Pass Transistor Circuits, Voltage Bootstrapping, Synchronous Dynamic Circuit Techniques, Dynamic CMOS Circuit Techniques, High Performance Dynamic CMOS Circuits
- **Semiconductor Memories**: Introduction, Dynamic Random Access Memory (DRAM), Static Random Access Memory (SRAM), Non-volatile Memory, Flash Memory.
- **Design for Testability**: Introduction, Fault Types and Models, Ad Hoc Testable Design Techniquues, Scan-Based Techniques, Built-In Self-Test (BIST) Techniques.

**MODULE-IV: 20% Institution Level** (Advanced topics)
- **Adavnce VLSI Design**: VLSI Design Styles, Computer-Aided Design Technologie, The CMOS P-Well Process
- **Modelling of MOS Transistor using SPICE**: Basic Concepts, The LEVEL 1 Modelling Equations, LEVEL 2 Model Equations, LEVEL 3 Model Equations.
- **Low Power CMOS Logic Circuits**: Estimation of Interconnect Parasitics, Calculation of Interconnect Delay of CMOS, Overview of Power Consumption, Low power Design through Voltage Scaling, Estimation and Optimization of Switching Activity, Reduction of Switchrd capacitance.

# Literature Reference
**Text Books**
  - Sung-Mo Kang and Yusuf Leblebici, CMOS Digital Integrated Circuits: Analysis and Design, 3rd Edn., Tata McGraw-Hill Publishing Company Limited, 2003 [Link](https://www.dropbox.com/s/5h4prayo3jr286r/Book-CMOS%20Digital%20Integrated%20Circuits%20Analysis%20%20Design%20by%20Sung-Mo%20%28Steve%29%20Kang%2C%20Yusuf%20Leblebici.pdf)
  - K. Eshraghian and N.H.E. Weste, Principles of CMOS VLSI Design – a Systems Perspective, 2nd Edn., Addison Wesley, 1993. [Link](https://www.dropbox.com/s/n2xpr6gr3upor80/Book-Weste-Harris-CMOS-VLSI-design-Pearson-4thEd-2011.pdf)
  - [Das10] Debaprasad Das, VLSI Design, Oxford University Press, New Delhi, 2010
  
**Reference Books**
- Wayne Wolf, Modern VLSI Design System – on – Chip Design, 3rd Edn., PHI
- Ian M. Rabaey, AnanthaChandrakasan, Borivoje Nikolic, Digital Integrated Circuits – A
Design Perspective, 2nd Edn., PHI [Link](https://www.dropbox.com/s/wsdpplskgq0ezzo/Book-Digital%20Integrated%20Circuits%20%282nd%20Edition%29%20by%20Jan%20M.%20Rabaey.pdf)
- John P. Uyemura, CMOS Logic Circuit Design, Springer (Kluwer Academic Publishers) 2001 [Link](https://www.dropbox.com/s/k7mgzlb6q8r74pm/Book-Circuit%20Design%20for%20CMOS%20VLSI%20by%20John%20P.%20Uyemura.pdf)
- Ken Martin, Digital Integrated Circuit Design, Oxford University Press, 2000 [Link](https://www.dropbox.com/s/uealymk8epn8n27/Digital%20integrated%20circuit%20design%20by%20Kenneth%20W%20Martin.pdf)

# Open Source EDA Setup
**LXLE-LINUX**
- Open source EDA setup: lxle linux in Virtual machine [Link](https://www.dropbox.com/s/2lovix0ntsw8yfw/2020-0917-Open%20Source%20EDA%20Setup.pdf)

# Course Materials (Theory) 
## Slides/Notes
- **Introduction**
  - 20/07/2020  Introduction [[Notes]](https://www.dropbox.com/s/mu4fs65j3ceway1/2020-0720-15VLSI7T-Introduction.pdf) || [[Video]](https://www.youtube.com/watch?v=HHlwbC_LZSw)
  - 21/07/2020 Introduction VLSI Design [[Notes]](https://www.dropbox.com/s/uilc6kyxp7bkxol/2020-0721-15VLSI7T-Introduction-to-VLSI-Design.pdf) || [[Video]](https://drive.google.com/file/d/1C0TYIpUiZVv3htd0byO2WtxbbwKU3PX4/view?usp=sharing)
  - 22/07/2020 History of VLSI [[Notes]](https://www.dropbox.com/s/n7j9bo3hnnm29xb/2020-0721-15VLSI7T-Module1-Lecture1-History-of-VLSI.pdf) || [[Video]](https://www.youtube.com/watch?v=C8EE-eFKE6c)
  - 27/07/2020 VLSI Design Style [[Notes]](https://www.dropbox.com/s/9t98ds4sgqe2i6j/2020-0727-15VLSI7T-Module4-Lecture1-VLSI-Design-Style.pdf) || [[Video]](https://www.youtube.com/watch?v=xlG6puE9-4s)
- **Fabrication of MOSFETs**
  - 28/07/2020 Fabrication of MOSFET-1 [Notes](https://www.dropbox.com/s/cgp9dgpaib12ozk/2020-0728-15VLSI7T-Module1-Lecture2-Fabrication-of-MOSFET.pdf)
  - 29/07/2020 Fabrication of MOSFET-2 [Notes](https://www.dropbox.com/s/lhjo31l4473t56a/2020-0729-15VLSI7T-Module1-Lecture3-Fabrication-of-MOSFET.pdf)
- **MOS Transistor**
  - 03/08/2020 Metal-Oxide-Semiconductor Stucture-1 [Notes](https://www.dropbox.com/s/ntcueemzmsbx9vb/2020-0803-15VLSI7T-Module1-Lecture-4-5-MOS-Transistor.pdf)
  - 05/08/2020 Metal-Oxide-Semiconductor Stucture-2 [Notes](https://www.dropbox.com/s/85kswvq4ejs08ha/2020-0805-15VLSI7T-Module1-Lecture6-MOS-Transistor.pdf)
  - 10/08/2020 Metal-Oxide-Semiconductor Stucture-3 [Notes](https://www.dropbox.com/s/xcipyfkiis1fbo5/2020-0810-15VLSI7T-Module1-Lecture7-8-MOS-Transistor.pdf)
  - 17/08/2020 Metal Oxide Semiconductor Field Effect Transistor-1 [Notes](https://www.dropbox.com/s/23z0n3p068hkgul/2020-0817-15VLSI7T-Module1-Lecture9-10-MOSFET.pdf)
  - 18/08/2020 Metal Oxide Semiconductor Field Effect Transistor-2 [Notes](https://www.dropbox.com/s/mqzd1o6u5y8qprn/2020-0818-15VLSI7T-Module1-Lecture11-12-MOSFET.pdf)
  - 19/08/2020 MOSFET Capacitance [Notes](https://www.dropbox.com/s/xxci3s9zu62b042/2020-0819-15VLSI7T-Module1-Lecture13-MOSFET-Capacitance.pdf)
- **MOS Inverters**
  - 24/08/2020 Static Characteristics [Notes](https://www.dropbox.com/s/6bosq72c78s964j/2020-0824-15VLSI7T-Module1-Lecture14-15-Inverter-Static.pdf)
  - 31/08/2020 Switching Characteristics and Delay Calculation [Notes](https://www.dropbox.com/s/ictagcl13jpd62v/2020-0831-15VLSI7T-Module1-Lecture16-17-Inverter-switching.pdf)
  - 01/09/2020 Static and Dynamic Power Dissipation [Notes](https://www.dropbox.com/s/yasjc7athn4gggx/2020-0901-15VLSI7T-Module1-Lecture18-19-Dynamic-Power.pdf)
  - 14/09/2020 Interconnect Parasitics [Notes](https://www.dropbox.com/s/1vicae5kih5flm0/2020-0914-15VLSI7T-Module4-Lecture3-Interconnect-Parasitics.pdf)
  - 15/09/2020 Inverter Chain Design [Notes](https://www.dropbox.com/s/1in6ofch4lxt7zv/2020-0915-15VLSI7T-Module2-Lecture25-26-Inverter-Chain-Design.pdf)
- **Combinational MOS Logic Circuits**
  - 07/09/2020 CMOS Logic Circuits, Complex Logic Circuits [Notes](https://www.dropbox.com/s/tpdidw4rtuvk9f4/2020-0907-15VLSI7T-Module2-Lecture20-21-Combinational-Logic.pdf)
  - 08/09/2020 CMOS Transmission Gate [Notes](https://www.dropbox.com/s/8xkxupbchyv9m9s/2020-0908-15VLSI7T-Module2-Lecture22-23-Transmission-Gate.pdf)
  - 09/09/2020 Pseudo NMOS Logic [Notes](https://www.dropbox.com/s/d0fsj5oyyjygusu/2020-0909-15VLSI7T-Module2-Lecture24-Pseudo-NMOS-Logic.pdf)
- **Sequential MOS Logic Circuits**
  - 21/09/2020 Latch and Flip-Flop Circuits [Notes](https://www.dropbox.com/s/0q6lvah7bk2j11e/2020-0921-15VLSI7T-Module2-Lecture28-29-Sequential-Circuits.pdf)
  - 21/09/2020 Sequential Logic Circuits [Slides](https://www.dropbox.com/s/uht871k7dje6hnj/2020-0921-15VLSI7T-Module2-Lecture28-29-Sequential-Circuits-Slides%28Kang-Book%29.pdf)
  - 22/09/2020 Setup, Hold and Propagation delay of D-FF [Notes](https://www.dropbox.com/s/xmpueuvrqmcsclv/2020-0922-15VLSI7T-Module2-Lecture30-31-Setup-Hold-Propagation-Delay-of-DFF.pdf)
- **Dynamic Logic Circuits**

# Course Materials (Laboratary) 
## Experiment/SpiceNetlist
  - 29/07/2020 Open Source EDA Setup [[Video]](https://www.youtube.com/watch?v=xt_r3TMzsCg)
  - 05/08/2020 Design and Simulation of RC Circuits using NGSpice [[Video]](https://www.youtube.com/watch?v=wQCPdbCgaME)
  - 12/08/2020 MOSFET Current-Voltage Characteristics [[Video]](https://www.youtube.com/watch?v=ZBNLN5PxwLg)
  - 19/08/2020 MOSFET Parameters Extraction using NGSpice [[Video]](https://www.youtube.com/watch?v=E5AnU98vG6I)
  - 26/08/2020 Inverter static Characteristics [[Video]](https://www.youtube.com/watch?v=WZwLIKsjjnY)
  - 02/09/2020 Inverter Dynamic Characteristics [[Video]](https://www.youtube.com/watch?v=bXUE3lW76nQ)
  - 09/09/2020 Combinational Circuit: NAND and NOR Gate [[Video]](https://www.youtube.com/watch?v=mZlzpoXuTtw)
  - 16/09/2020 RC Interconnect: Lumped and Distributed RC Model [[Video]](https://www.youtube.com/watch?v=MhvBJUcM-HI)
  - 23/09/2020 CMOS D-Latch and D-Flif-flop [[Video]](https://www.youtube.com/watch?v=RG6zZbfs0Yg)
  
  - 23/09/2020 Design and Simulation of CMOS D-Latch [Reports](https://www.dropbox.com/s/wtxsf73gfdg308x/2020-0923-15VLSI7T-LAB-Exp_8-D-Latch.pdf)
  - 23/09/2020 Design and Simulation of CMOS D-Flip-Flop [Reports](https://www.dropbox.com/s/4283x6xd7x5vkfh/2020-0923-15VLSI7T-LAB-Exp_8-D-Flip-Flop.pdf)
  
  
* * *
[Kang03]:       https://www.dropbox.com/s/50bgttdqbfbtgek/Kang-CMOS-DigitalICAnalysis%26Design-McGraw-2nd-2003.pdf
[Weste11]:      https://www.dropbox.com/s/ard8jntcpq1pt45/Weste-Harris-CMOS-VLSI-design-Pearson-4thEd-2011.pdf
[Clein00]:      https://www.dropbox.com/s/xw2yi6khzm1jj5m/Clein-cmos-ic-layout-concepts-methodologies-and-tools-2000.pdf

