# Kathara Network Topology
This repository contains a network simulation project using Kathara, designed for academic purposes.

The project focuses on network topology creation and configuration, covering key aspects such as:

- Setting up **routers, PCs, and servers** with static IP addresses.
- Implementing **routing protocols**, including **OSPF and BGP**, for dynamic and static routing.
- Configuring **firewalls, NAT, and VPN services** to enhance network security.
- Setting up an **SSH server** with public key authentication for secure remote access.
- Capturing and analyzing network traffic for troubleshooting and validation.

The lab is structured to replicate a realistic network environment, allowing hands-on experience in designing and configuring networks. The setup follows a structured lab.conf configuration and includes all necessary scripts and commands to deploy the network efficiently.

### Network Topology Overview
The following diagram represents the initial network topology, which serves as the foundation for the configuration and implementation of routing, security policies, and VPN services.

![image](https://github.com/user-attachments/assets/9e854937-7c29-4922-923d-fab8c51b7f22)

## Using Kathara and Docker for Network Simulation
This lab has been implemented using Kathara, a lightweight network emulation tool that allows the simulation of complex network topologies using container-based virtualization through Docker.

### How Kathara Uses Docker
- Each network node (routers, PCs, servers) runs inside an isolated Docker container.
- Kathara manages container lifecycles, ensuring that network topologies can be easily started, stopped, and modified.
- Bridges and virtual interfaces are created dynamically to simulate real-world network connections.
- Docker’s lightweight architecture ensures that simulations run efficiently without the need for full-fledged virtual machines.
### Lab Structure
- The topology is defined in the _lab.conf_ file, specifying nodes and network connections.
- Individual configurations for routers, PCs, and servers are stored within their respective directories.
- Routing, firewall, and VPN settings are applied dynamically through configuration files and scripts.

## ✍️ Author
Name: Mattia Baldinetti

Course: Network Infrastructures (Cybersecurity)

University: La Sapienza University of Rome

