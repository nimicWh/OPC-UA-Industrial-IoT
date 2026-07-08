# OPC UA Industrial IoT

An Industrial Internet of Things (IIoT) demonstration using an IoT gateway as an OPC UA Server, allowing industrial data to be accessed by an OPC UA Client application.

> **Project Year:** 2018
> **Status:** Completed (Archived Project)

---

# Overview

This project was developed in **2018** to demonstrate how industrial data collected by an IoT gateway can be exposed through an **OPC UA Server** for interoperability with industrial software.

The IoT gateway was configured as an **OPC UA Server** using **Node-RED**, enabling industrial process data to be accessed by an external **OPC UA Client** developed by **Integration Objects**.

The project demonstrates the integration of Industrial IoT (IIoT) technologies with the OPC UA communication standard widely used in industrial automation and Industry 4.0 environments.

---

# Project Objectives

* Configure an IoT gateway as an OPC UA Server
* Publish industrial process data using OPC UA
* Connect an external OPC UA Client
* Demonstrate interoperability between industrial systems
* Explore Industry 4.0 communication standards

---

# System Architecture

```text id="jlwmgw"
Industrial Device / Sensors
           │
           ▼
      IoT Gateway
       (Node-RED)
           │
           │ OPC UA Server
           ▼
     OPC UA Client
 (Integration Objects)
```

---

# Project Highlights

* OPC UA Server implementation
* Node-RED integration
* Industrial IoT gateway
* OPC UA Client communication
* Real-time industrial data exchange
* Industry 4.0 interoperability

---


## 1. OPC UA Server on IoT Gateway

The IoT gateway was configured using **Node-RED** to function as an OPC UA Server, exposing industrial process variables to connected OPC UA clients.

<img width="2048" height="1536" alt="Node-RED OPC UA Server" src="https://github.com/user-attachments/assets/80dce03b-d696-49c9-afe3-7bcfbec3ed1c" />

---

## 2. OPC UA Client

The **Integration Objects OPC UA Client** was used to establish communication with the gateway and browse the available OPC UA data nodes.

<img width="1536" height="2048" alt="OPC UA Client" src="https://github.com/user-attachments/assets/faf6a860-babe-4274-a3b0-2d7a3f9ca4a0" />

---

## 3. Real-Time Data Monitoring

The OPC UA Client successfully connected to the IoT gateway and displayed real-time process data published by the OPC UA Server.

<img width="2048" height="1536" alt="OPC UA Data" src="https://github.com/user-attachments/assets/27ade613-854c-4ed7-aa40-c21ab17e0cd0" />

---

# Technologies Used

* OPC UA
* Node-RED
* OPC UA Server
* OPC UA Client
* Integration Objects OPC UA Client
* Industrial IoT (IIoT)
* Ethernet Networking

---

# Demonstrated

* OPC UA Server Configuration
* OPC UA Client Integration
* Industrial Networking
* Node-RED Development
* Industrial Communication Protocols
* Industrial IoT Architecture
* OT/IT Integration
* Industrial Data Exchange

---

# Outcomes

* Configuring an IoT gateway as an OPC UA Server
* Publishing industrial process data using OPC UA
* Connecting industrial software through standard communication protocols
* OPC UA client/server architecture

---

# Potential Applications

* Smart Manufacturing
* Factory Automation
* SCADA Systems
* Industrial Monitoring
* Machine Data Collection
* Manufacturing Execution Systems (MES)
* Predictive Maintenance
* Industry 4.0 Integration

---

# Notes

This project was completed in **2018** as a proof of concept demonstrating Industrial IoT communication using the OPC UA standard.

The project shows an IoT gateway as an OPC UA Server and enabling interoperability with industrial client applications. The architecture reflects common Industry 4.0 practices for securely exchanging data between industrial equipment, gateways, and supervisory software.
