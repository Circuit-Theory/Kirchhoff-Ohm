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
  Student ID: 19390005<br>
  <strong>Nikolaos Katsos</strong><br>
  Student ID: 21390084
</p>

<p align="center">
  Supervisor: Christos Kampouris, Laboratory Teaching Staff<br>
  Co-supervisor: Georgios Antoniou, Laboratory Teaching Staff
</p>

<p align="center">
  Athens, April 2022
</p>


## Overview

This repository contains the documentation for a laboratory project conducted at the **University of West Attica**, within the **Department of Computer and Informatics Technology and Computer Engineering**.  
The project focuses on the **theoretical**, **simulated**, and **experimental** verification of fundamental electrical laws.

---

## Table of Contents

| Section | Title          | Description                                    |
|--------:|----------------|------------------------------------------------|
| assign  | Assignment     | Contains assignments and tasks                 |
| docs    | Documentation  | Project documentation, guides, and notes       |
| multisim     | Multisim    | All souce multisim files implementing the circuits      |

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

## Installation Guide

Clone this repository to your local machine. 
```bash
git clone https://github.com/Circuit-Theory/Kirchhoff-Ohm.git
``` 
