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
  <strong>Circuit Theory</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Kirchhoff's Laws - Ohm Law - Potentiometer - Rheostat
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
  <strong>Nikolaos Katsos</strong><br>
  Student ID: 21390084
</p>


<p align="center">
  Supervisor: Christos Kampouris, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.syros.aegean.gr/en/staff/research-staff/phd-candidates/christos-kampouris" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Co-supervisor: Georgios Antoniou, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/georgios-antoniou/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, April 2022
</p>

---

# Project Overview

This repository contains the documentation for a laboratory project conducted at the **University of West Attica**, within the **Department of Computer and Informatics Technology and Computer Engineering**.  
The project focuses on the **theoretical**, **simulated**, and **experimental** verification of fundamental electrical laws.

---

## Table of Contents

| Section | Folder | Description |
|------:|--------|-------------|
| 1 | `assign/` | Assignment material for the Circuit Theory course |
| 1.1 | `assign/circuit theory rev2021_EXERCISE_1st.pdf` | Assignment description in English |
| 1.2 | `assign/θεωρία κυκλωμάτων rev2021_ΑΣΚΗΣΗ_1η.pdf` | Assignment description in Greek |
| 2 | `docs/` | Documentation on Kirchhoff’s Laws, Ohm’s Law, potentiometer, and rheostat |
| 2.1 | `docs/Kirchhoff-Ohm-Potentiometer-Rheostat.pdf` | English documentation |
| 2.2 | `docs/Κίρκοφ-Ωμ-Ποτενσιόμετρο-Ροοστάτης.pdf` | Greek documentation |
| 3 | `multisim/` | Circuit simulation files and visual outputs |
| 3.1 | `multisim/1stLawKirchhoff/` | Multisim files and images for Kirchhoff’s First Law |
| 3.2 | `multisim/2ndLawKirchhoff/` | Multisim files and images for Kirchhoff’s Second Law |
| 3.3 | `multisim/LawOfOhm/` | Simulations for Ohm’s Law |
| 3.3.1 | `multisim/LawOfOhm/RChange/` | Output images for resistance variation |
| 3.3.2 | `multisim/LawOfOhm/VoltChange/` | Output images for voltage variation |
| 3.3.3 | `multisim/LawOfOhm/*.ms14` | Multisim project files for Ohm’s Law variants |
| 3.4 | `multisim/Potentiometer/` | Potentiometer simulation files and output images |
| 3.5 | `multisim/Rheostat/` | Rheostat simulation files and output images |
| 3.6 | `multisim/VoltDividerVariant.ms14` | Voltage divider variant simulation |
| 4 | `README.md` | Repository overview and usage instructions |

---

## Project Overview

The primary objective of this project is to verify **Kirchhoff's Laws** and **Ohm’s Law** through three distinct approaches:

- **Theoretical analysis**
- **Software simulation** using *Multisim*
- **Physical laboratory experimentation**

---

## Core Topics Covered

- **Kirchhoff’s First Law (Current Law – KCL)**  
  Verification that the sum of currents entering a node is equal to the sum of currents leaving it.

- **Kirchhoff’s Second Law (Voltage Law – KVL)**  
  Verification that the algebraic sum of voltages around any closed loop is zero.

- **Ohm’s Law**  
  Analysis of the relationship between voltage, current, and resistance.

- **Circuit Applications**  
  Investigation of resistance connections, including the use of resistors as **potentiometers** and **dimmers**.

---

## Experimental Setup

### Equipment Used

The following laboratory equipment was utilized during the experimental phase:

- **Breadboard and Connection Cables**  
  Used for assembling the electrical circuits.

- **Fixed Resistors**  
  Values of **4.7 kΩ** and **1 kΩ**.

- **Digital Bench Multimeter**  
  Configured as a **voltmeter** to set and verify the DC source voltage.

- **Analog Multimeter**  
  Configured as an **ammeter** for current measurements.

- **Potentiometer**  
  Used for experiments involving variable resistance.

---

## Key Results

### Kirchhoff’s First Law Verification (KCL)

In the simulated circuit (Figure 2), a **10 V DC source** was applied:

- **Total Current (XMM1):** 1.027 mA  
- **Branch Currents (XMM2, XMM3, XMM4):** 342.466 μA each  

**Verification:**  
The sum of the three branch currents equals the total current entering the node:

```
342.466 μA × 3 ≈ 1.027 mA
```
This confirms **Kirchhoff’s First Law**.

---

### Kirchhoff’s Second Law Verification (KVL)

Using a **series circuit** (Figure 5) with a **10 V DC source**:

- The sum of voltage drops across resistors **R₁**, **R₂**, and **R₃** was equal to the applied source voltage.
- The circuit operated correctly as a **voltage divider**.

**Conclusion:**  
The experimental and simulated measurements verified **Kirchhoff’s Second Law**, demonstrating that the total potential difference around a closed loop is zero.

---

# Installation & Setup Guide

This repository contains laboratory simulations and analysis for **Circuit Theory**, focusing on **RLC series and parallel circuits** and their resonance behavior.  

All simulations are implemented in **NI Multisim**.

---

## Prerequisites

### Required Software
- **NI Multisim 14** (or later)  
  Ensure your system meets the requirements for running `.ms14` files.  
  Download from [NI Multisim](https://www.ni.com/en-us/shop/electronic-test-instrumentation/application-software-for-electronic-test-and-instrumentation-category/what-is-multisim.html).

### Optional Software
- **PDF Viewer** for documentation: `Kirchhoff-Ohm-Potentiometer-Rheostat.pdf` / `Κίρκοφ-Ωμ-Ποτενσιόμετρο-Ροοστάτης.pdf`

---

## Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/Circuit-Theory/Kirchhoff-Ohm.git
```

### 2. Navigate to Project Directory
```bash
cd Kirchhoff-Ohm
```
Ensure the following folder structure exists:
```bash
assign/
docs/
multisim/
```

---

### 3. Open a Simulation in Multisim
- Launch NI Multisim.
- Select File → Open.
- Navigate to the `multisim/` folder.
- Open the desired `.ms14` file (series or parallel circuit).
- Wait for the circuit topology to load.

---

## Open the Documentation
1. Navigate to the `docs/` directory
2. Open the report corresponding to your preferred language:
    - English: `Kirchhoff-Ohm-Potentiometer-Rheostat.pdf`
    - Greek: `Κίρκοφ-Ωμ-Ποτενσιόμετρο-Ροοστάτης.pdf`
