# FPGA-Based Hyperchaotic Secure IoT Communication System

## Overview
This project implements a **Hyperchaotic Encryption and Decryption System on FPGA** for securing communication in Internet of Things (IoT) devices data.

Traditional encryption methods may not always meet the requirements of **low power, real-time processing, and high security** needed for IoT networks. To address this, this project uses **hyperchaotic systems** to generate highly unpredictable encryption keys.

The system is implemented using **Verilog HDL** and validated using FPGA simulation tools.

---

## Key Features

- FPGA based hardware encryption
- Hyperchaotic key generation
- Secure IoT data communication
- Real-time encryption and decryption
- Verilog HDL implementation
- Simulation and verification using FPGA tools

---

## Concept

Hyperchaotic systems are nonlinear dynamic systems that produce **extremely complex and unpredictable signals**.

These signals are used as **encryption keys**, making it very difficult for attackers to predict or break the encryption.

In this project:

1. Chaotic signals are generated using a **Lorenz-based hyperchaotic system**
2. These signals generate dynamic encryption keys
3. Data from IoT devices is encrypted
4. The receiver decrypts the data using the same chaotic system

---

## System Architecture

The system consists of the following modules:

### 1. Hyperchaotic Generator
Generates chaotic sequences used as encryption keys.

### 2. Encryption Module
Encrypts incoming IoT data using chaotic keys.

### 3. Decryption Module
Decrypts the encrypted data at the receiver side.

### 4. Top Module
Controls data flow between encryption and decryption blocks.

### 5. Testbench
Verifies functionality of the entire system.

---

## Project Structure

---

## Tools Used

- Verilog HDL
- Xilinx Vivado / ModelSim
- FPGA Development Board (Spartan6 (XC6SLX9) Specifications
- Simulation tools for verification

---

## Applications

- Secure IoT communication
- Smart home systems
- Industrial IoT security
- Military communication systems
- Secure wireless sensor networks

---

## Advantages

- High security due to chaotic behavior
- Hardware-level encryption
- Fast real-time operation
- Suitable for resource constrained IoT devices

---

## Future Improvements

- Hardware implementation on FPGA board
- Integration with IoT sensors
- Real-time wireless communication
- Optimization for low power devices
- Designing ASIC for the security of iot data

---

## Author

**Kiran Gorajanal**

Electronics and Communication Engineering  
FPGA | Embedded Systems | VLSI Enthusiast

---

## License

This project is open-source and available for educational and research purposes.
