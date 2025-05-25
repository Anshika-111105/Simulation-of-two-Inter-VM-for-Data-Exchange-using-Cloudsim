# Simulating Inter-VM Data Exchange in Cloud Computing

This presentation explores the simulation and optimization of data exchange between virtual machines (VMs) within cloud computing environments using **CloudSim**. It aims to provide insights into efficient data transfer mechanisms and performance improvements in virtualized infrastructures.

## 📌 Project Overview

**Goal:**  
To simulate and analyze different methods of inter-VM data exchange in cloud systems to reduce latency, improve security, and optimize resource usage.

**Tool Used:**  
- **CloudSim** – A simulation toolkit for cloud computing environments.

## 👥 Team Members & Responsibilities

- **Anshika Saklani** – Cloud Broker module development and task/data allocation management  
- **Manya Chauhan** – Datacenter configuration and virtual machine hosting  
- **Akriti Rawat** – Simulation class implementation and experiment setup  

## 💻 Key Concepts Covered

### 🔹 Cloud Computing and Virtual Machines
- **Role of VMs:** Execution environments for applications and data processing.
- **Challenges:** High latency, security concerns, and inefficient resource allocation.

### 🔹 Types of Virtualization
- **System-to-System Virtualization:**
  - Multiple OS instances on shared hardware.
  - Inter-VM data transfer via networks or shared resources.
- **Application Virtualization:**
  - Isolated app execution.
  - Seamless and secure data exchange using APIs and structured messaging.

### 🔹 Data Types Exchanged
- File Data
- Streaming Data (e.g., telemetry, video)
- Messages & API Calls
- Shared Memory Data

## 🧪 CloudSim Simulation Architecture

**Components:**
- **CloudSim Framework** – Manages the simulation environment.
- **Datacenter** – Hosts virtual machines.
- **Cloud Broker** – Allocates tasks and manages data transfers.

**Data Exchange Methods Simulated:**
- Direct VM-to-VM communication
- Shared storage use
- Network-based data transfer

### 🖼️ Simulation Architecture Diagram

![Simulation Architecture](https://github.com/Anshika-111105/Simulation-of-two-Inter-VM-for-Data-Exchange-using-Cloudsim/blob/main/cloud_sim.jpg)

*Figure: Visual representation of data exchange simulation using CloudSim.*

## ⚙️ Outcomes and Optimizations

- **Reduced Latency:** Identifying bottlenecks in VM communication.
- **Improved Security:** Simulated secure exchange mechanisms.
- **Efficient Resource Use:** Enhanced bandwidth and CPU allocation.

## 🔭 Future Directions

- Explore more diverse data exchange models.
- Enhance simulation realism with detailed network/hardware parameters.
- Translate results to real-world cloud infrastructure for optimization.

