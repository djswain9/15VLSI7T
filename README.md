# Table of Contents 
- [Overview](#Overview)
- [Install/Setup](#Installation-Setup)
    - [Cloning the Repo](#Cloning-the-Repository)
    - [Setting the Environment Variables](#Setting-the-Environment-Variables)
    - [Suggested Directory Structure](#Suggested-Directory-Structure)

# Overview

This is the repository for the VLSI Design Course for 7th Sem AEI, 2020. This repo contains the eda tools, Labs, assignments, docs, etc. related to the course.

# Installation Setup

## Cloning the Repository
```bash
git clone https://www.github.com/silicon-vlsi/15VLSI7T
```

## Setting the Environment Variables
Add the following in ```~/.bashrc```
```bash
export PATH=$PATH:<PATH-TO-REPO>/15VLSI17T/eda/ngspice-32/glnxa64/bin
```
## Suggested Directory Structure
```bash
<HOME_DIR>          [eg. /home/vlsi]
    ├── 15VLSI7T      [Git Repo, DO NOT WORK IN THIS DIR]
    ├── Desktop
          ├── myLab    [Your Wok Directory]
```
**NOTE** :
>*BUGS DETECTED* -(once you *source* your (.sp file) after entering ngspice sim>ulator,the file seems to disappear the next time u search it in your directory

>(That's because there is an error while editing the fie in ngspice simulator..

>*DEBUG*:
>source and run in batch mode
  -*Sourcing*:
```bash
/home/vlsi/../../ ngspice circuit.sp
```
 -*Run*:
```bash
ngspice -b -r sim.raw -o sim.log sim.sp
```

>(Then it will run ngspice,store the output in *sim.raw* and log file in *sim.l>og* and not enter ngspice in interactive mode..)
   
