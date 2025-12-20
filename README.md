# Development of an Open Source RTL-to-GDS Digital Implementation Flow for Instructional Use

This repository contains the work carried out over an entire semester as part of an undergraduate project at IITK, under the guidance of Prof. Chithra. The project focuses on developing and evaluating an **open-source digital implementation flow** for instructional use in the lab sessions of EE619: VLSI System Design, a graduate-level course on digital IC design offered at the institute. The work explores the use of modern open-source EDA tools to demonstrate key stages of the digital design flow, from RTL design and logic synthesis to timing, power analysis, and physical design, without relying on proprietary tools or restricted PDKs.

## Toolchain
The implementation flow uses the following open-source tools:
* **Yosys** - Logic synthesis
* **OpenSTA** - Static timing and power analysis
* **OpenROAD** - Physical design
* **Nangate45** - 45nm standard-cell library

All tools and libraries are packaged using **Docker** to ensure reproducible setup and easy deployment on lab machines.
