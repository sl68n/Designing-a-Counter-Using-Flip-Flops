# Designing a Counter Using Flip-Flops

![Course](https://img.shields.io/badge/Course-CPCS211-orange)
![Type](https://img.shields.io/badge/Project-Digital%20Logic-blue)
![Topic](https://img.shields.io/badge/Topic-Sequential%20Circuits-purple)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

This project implements a custom 3-bit counter using both D Flip-Flops and JK Flip-Flops.

Developed for CPCS-211 (CS3) – Digital Logic Design  
King Abdulaziz University – Fall 2024

---

## Project Overview

The project focuses on designing and implementing a synchronous counter with a toggle control input (T).

The counter supports:

- Forward sequence (T = 1)
- Reverse sequence (T = 0)

The design includes:

- State tables
- Excitation tables
- Karnaugh Map (K-Map) simplification
- Boolean expression derivation
- Circuit implementation using:
  - D Flip-Flops
  - JK Flip-Flops

---

## Counter Sequence

### Forward Sequence (T = 1)

0 → 1 → 7 → 5 → 3 → 4 → 6 → 2 → 0

Binary sequence:

000 → 001 → 111 → 101 → 011 → 100 → 110 → 010 → 000

---

### Reverse Sequence (T = 0)

0 → 2 → 6 → 4 → 3 → 5 → 7 → 1 → 0

Binary sequence:

000 → 010 → 110 → 100 → 011 → 101 → 111 → 001 → 000

---

## D Flip-Flop Implementation

### Steps Included:

- State Table Construction
- Derivation of:
  - D2
  - D1
  - D0
- Boolean expressions
- K-Map simplification
- Final logic circuit implementation

---

## JK Flip-Flop Implementation

### Steps Included:

- State Table Construction
- Derivation of:
  - J2, K2
  - J1, K1
  - J0, K0
- K-Map simplification
- Final synchronous circuit implementation

---

## Concepts Applied

- Sequential circuit design
- Flip-flop excitation tables
- Karnaugh Maps (K-Maps)
- Boolean algebra simplification
- Forward & reverse counter design
- Synchronous state transitions

---

## Learning Outcomes

This project demonstrates:

- Understanding of state machine design
- Ability to derive excitation equations
- Implementation of counters using different flip-flop types
- Optimization using Karnaugh Maps

---

## Academic Information

Course: CPCS-211 – Digital Logic Design  
University: King Abdulaziz University  
Semester: Fall 2024  

Student:  
Sultan Yasir Alasami  
ID: 2339663
