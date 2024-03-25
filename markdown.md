# Guide to Using Docker with R interactive in RIS
> [!NOTE] Created on 02/19/2024
> By [Chenyu Yang](chenyu.y@wustl.edu)

# **Introduction**

This guide is designed to help lab members utilize Docker containers to interact with data files using R. Docker ensures a consistent environment across different machines, facilitating reproducible research. R is a powerful tool for data analysis, allowing for complex data manipulation and analysis tasks.

This file can be found in `\\storage1.ris.wustl.edu\belloy\Active\01_References\04_HowTo\Docker_Info\Example\R_interactive`

*In macOS, directory paths use forward slashes instead of backslashes.*

# **Getting Started with Docker and R**

## Docker

> The technical definition of Docker is an open-source project that automates the deployment of software applications inside containers by providing an additional layer of abstraction and automation of OS-level virtualization on Linux.
The simpler definition is that Docker is a tool that allows users to deploy applications within a sandbox (containers) to run on the host operating system (RIS Compute Platform).
This method allows for all dependencies and environments to be able to remain unique to the software without interacting or interfering with other software’s environments.
> 

Download and install from here

[![Docker Desktop](/images.png "Docker Desktop")](https://www.docker.com/products/docker-desktop/)

*If you encounter any issues downloading this software, please request admin access from [Prof.  Belloy](belloy@wustl.edu "belloy@wustl.edu").*
