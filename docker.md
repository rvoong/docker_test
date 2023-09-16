Docker is a virtualization software
* Makes developing and deploying applications much easier 
* Packages application with all the necessary dependencies, configuration, system tools and runtime

Each developer needs to install and configure all services directly on their OS 
Many steps where something can go wrong 

Opeartions only needs to get an artifact of Docker which makes it easier to fetch and run. 

# How does Docker run its containers?
2 Main Layers
OS applications Layer
OS Kernel 
Hardware (Kernel communicates with this)

Docker virtualizes the application layer. Uses the kernel of the host
* Size of the docker images are smaller
* Containers are much faster to start 
* Dockers are compatible with only Linux distro
* Most containers are linux based
* Docker desktop is available for windows MAC
    * Hypervisor layer with lightweight linux distro

Docker Image: Executable application artifact
Add environment variables
Create Directories, files, etc.

Docker Container: A running instance of an image
From one image, you can run multiple containers




# Install Docker 

Virtual Machine virtualizes the application layer and the kernel
VM is compatible with all OS



# Question
1. What is the difference between virtualenv and Docker

A virtualenv only encapsulates Python dependencies. A Docker container encapsulates an entire OS.