<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Logic Design</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Logic Gates
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.researchgate.net/profile/Eleni-Tsalera-2" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, April 2021
</p>

---

# Project Overview

This README provides an overview of the **Digital Design Workshop 1** report submitted to the **University of West Attica**. The project focuses on the **theoretical study**, **simulation**, and **implementation** of fundamental logic gates.

---

## Table of Contents

| Section | Folder/File | Description |
|------:|-------------|-------------|
| 1 | `assign/` | Assignment material for the Logic Gates workshop |
| 1.1 | `assign/ASSIGNMENT 1.pdf` | Assignment description in English |
| 1.2 | `assign/ΕΡΓΑΣΙΑ 1.pdf` | Assignment description in Greek |
| 2 | `docs/` | Documentation covering logic gates theory and implementations |
| 2.1 | `docs/Logic-Gates.pdf` | English documentation for logic gates |
| 2.2 | `docs/Λογικές-Πύλες.pdf` | Greek documentation for logic gates |
| 3 | `multisim/` | Multisim logic gate simulation files |
| 3.1 | `multisim/AND.ms14` | AND gate simulation |
| 3.2 | `multisim/NAND.ms14` | NAND gate simulation |
| 3.3 | `multisim/NOR.ms14` | NOR gate simulation |
| 3.4 | `multisim/NOT.ms14` | NOT gate simulation |
| 3.5 | `multisim/OR.ms14` | OR gate simulation |
| 3.6 | `multisim/propagationDelay.ms14` | Propagation delay demonstration circuit |
| 3.7 | `multisim/XNOR.ms14` | XNOR gate simulation |
| 3.8 | `multisim/XOR.ms14` | XOR gate simulation |
| 4 | `README.md` | Repository overview and usage instructions |

---

## Project Overview

- **Institution:** University of West Attica  
- **Department:** Information and Computer Engineering  
- **Course:** Digital Design – Workshop 1  
- **Student:** Athanasiou Vasileios Evangelos  
- **Tools Used:** Multisim simulator for circuit design and analysis

---

## Objectives

The main goal of this work is to demonstrate the operation of various logic gates using:

- Truth tables
- Logical equations
- Simulated implementations

The report covers:

- **Basic Gates:** AND, OR, NOT
- **Universal Gates:** NAND, NOR
- **Exclusive Gates:** XOR, XNOR
- **Advanced Analysis:** Propagation delay measurement using four AND gates connected in series with a 100 kHz square pulse.

---

## Technical Summary of Gates

| Gate | Logic Equation | Behavior Summary |
|------|----------------|------------------|
| AND | F = A · B | Output is high only when both inputs are high. |
| OR | F = A + B | Output is high if at least one input is high. |
| NAND | F = ¬(A · B) | Inverted AND; output is low only when both inputs are high. |
| NOR | F = ¬(A + B) | Inverted OR; output is high only when both inputs are low. |
| XOR | F = A ⊕ B | Output is high only when inputs differ. |
| XNOR | F = ¬(A ⊕ B) | Output is high when inputs are equal. |

---

## Implementation Details

The simulation environment uses the following components:

- **Logic "1":** Represented by VCC source (5V)
- **Logic "0":** Represented by Ground (0V)

### Visual Indicators
- Lamps (2.5V) are used to indicate input and output states.
- A lit lamp represents logic **1**.

### Switching
- Switches S1 and S2 toggle inputs between VCC and Ground.

---

## Report Structure

- **Chapter 1:** Introduction and basic gate operation
- **Chapter 2:** Bibliography and references
- **Chapter 3:** Multisim implementation and components description
- **Chapter 4:** Exercises including truth tables, simulations, and propagation delay analysis

---

## Conclusion

This workshop establishes a foundation in digital electronics by demonstrating how logic gates operate and how they can be analyzed through simulation, forming the basis for more advanced digital circuit design.

---

---

# Installation & Setup Guide

This repository contains laboratory simulations and documentation for **Digital Design – Workshop 1**, focusing on the behavior and implementation of **basic logic gates**.

All circuit simulations are implemented using **NI Multisim**.

---

## Prerequisites

### Required Software
- **NI Multisim 14** or later  
  Required to open and run `.ms14` simulation files.

Download from:  
https://www.ni.com/en-us/shop/electronic-test-instrumentation/application-software-for-electronic-test-and-instrumentation-category/what-is-multisim.html

---

### Optional Software
- **PDF Viewer** to open workshop documentation.
- **Git** for cloning the repository.

---

## Installation Steps

### 1. Clone the Repository

Clone using Git:

```bash
git clone https://github.com/Logic-Design-aka-Uniwa/Logic-Gates.git
```

Alternatively, download the repository as a ZIP file and extract it locally.

### 2. Navigate to Project Directory
```bash
cd Logic-Gates
```

Ensure the following structure exists:

```bash
assign/
docs/
multisim/
README.md
```

---

## Multisim Simulation Files
The repository includes simulation files demonstrating the operation of logic gates.
Typical circuits include implementations of:

| Gate Type               | Description                         |
|-------------------------|-------------------------------------|
| AND                     | Logical multiplication               |
| OR                      | Logical addition                     |
| NOT                     | Signal inversion                     |
| NAND                    | Universal gate                       |
| NOR                     | Universal gate                       |
| XOR                     | Exclusive OR                         |
| XNOR                    | Exclusive NOR                        |
| Propagation Delay Circuit | Four AND gates in series for timing analysis |

### 3. Open a Simulation in Multisim
1. Launch **NI Multisim**.
2. Select **File** → **Open**.
3. Navigate to the repository folder.
4. Open the `multisim/` directory.
5. Select the desired `.ms14` file.
6. Wait for the circuit to load.
7. Press Run to start simulation.

---

## Opening the Documentation
1. Navigate to the `docs/` folder.
2. Open the available documentation file(s) to review:
    - Gate theory
    - Truth tables
    - Simulation analysis
    - Propagation delay experiments