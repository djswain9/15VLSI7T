# Table of Contents 
- [Overview](#Overview)
    - [Cloning the Repo](#Cloning-the-Repository)
    - [Suggested Directory Structure](#Suggested-Directory-Structure)
- [NGSpice](#NGSpice)    
    - [Quick Start Guide](#Quick Start Guide)
- [Technology](#Technology)
    - [MOSIS Scalable CMOS (SCMOS)](#MOSIS Scalable CMOS (SCMOS))

# Overview

This is the repository for the VLSI Design Course for 7th Sem AEI, 2020. This repo contains the eda tools, Labs, assignments, docs, etc. related to the course.

## Cloning the Repository
```bash
git clone https://www.github.com/silicon-vlsi/15VLSI7T
```
## Suggested Directory Structure
```bash
<HOME_DIR>          [eg. /home/vlsi]
    ├── 15VLSI7T      [Git Repo, DO NOT WORK IN THIS DIR]
    ├── Desktop
          ├── myLab    [Your Wok Directory]

```

# NGSpice
[NGSpice] is a open source spice simulator for electric and electronic circuits. 
- [NGSpice Reference Manual][NGSpiceMan]: Comple reference manual in HTML format.

After cloning this repo, a precompiled version (compiled in 64-bit LXLE/Ubuntu) will be available in `<PATH-TO-REPO>/15VLSI7T/eda/ngspice-32`. Add the following environment variables in your `~/.bashrc`
```bash
export  SPICE_LIB_DIR=$HOME/projects/15VLSI7T/eda/ngspice-32/glnxa64/share/ngspice
export  SPICE_EXEC_DIR=$HOME/projects/15VLSI7T/eda/ngspice-32/glnxa64/bin
export  PATH=$PATH:$SPICE_EXEC_DIR
```
There is a initialization script in `$SPICE_LIB_DIR/scripts/spinit`. You can overwrite any of the initilization by adding commands to a local `~/.spiceinit` .
The directory stucture:
```bash
15VLSI7T/eda/ngspice-32
├── doc
│   └── ngspice-32-manual.pdf  (Complete Reference)
├── examples                   (Lots of Spice examples)
├── glnxa64
│   ├── bin
│   ├── include
│   └── share
│       ├── man
│       └── ngspice
│           └── scripts        (Scripts, including startup spinit)
└── models                     (Spice models)
```
## Quick Start Guide
```bash
You can open a text editor create a *netlist* of the intended circuit for example of a voltage divider as shown below (say filename `divider.sp`):
```spice
First line in ngspice is always the title line
* This is a comment line
Vbat    vin     0       DC 5
R1      vin     vout    1k
R2      vout    0       1k

.control
tran 0.1u 1u
.endc

.end
```
Then start `ngspice` and source the netlist at the ngspice command prompt:
```bash
ngspice 1 -> source divider.sp
```
It should output the node voltages at the initial transient voltages. you can plot any of the nodes eg.:
```bash
ngspice 3 -> edit
```
And to quit simply type `quit`.

# Technology
## MOSIS Scalable CMOS ([SCMOS])
```bash
[SCMOS] is a *lambda-based* scalable design rules that can be interfaced to many CMOS fabrication process available at MOSIS. **NOTE** The scalable design rules does not interface with Fabs now because of lot unique process nuances.

- The Spice model files are located at `<PATH-TO-REPO>/project2020/eda/ngspice-32/models/scn4m_subm`
- Typical MOS parameters:
  - **NMOS**: tox=7.6nm, nch=1.7e17/cm^3, Vt0=0.49V, un(mobility)=445 cm^2/Vs
  - **PMOS**: tox=7.6nm, nch=1.7e17/cm^3, Vt0=-0.66V, up(mobility)=151 cm^2/Vs


* * *

[SCMOS]:                https://www.mosis.com/files/scmos/scmos.pdf
[NGSpice]:              http://ngspice.sourceforge.net
[NGSpiceMan]:           http://ngspice.sourceforge.net/docs/ngspice-html-manual/manual.xhtml
[Magic]:                http://opencircuitdesign.com/magic/




