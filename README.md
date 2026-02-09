# Railway Timetable Optimisation System

This repository contains a Python-based optimisation system developed as part of my Bachelor's thesis in Computer Engineering (Automation Systems).

The purpose of the project is to insert an additional train into an existing railway timetable without affecting the stability, timing, or structure of the original schedule.

## Technologies Used

- **Python**  
- **Pandas** for data manipulation  
- Dynamic programming for constraint-based optimisation  

## Problem Overview

Railway timetables involve complex constraints such as:

- bidirectional flows
- single-track sections
- real operational data
- time overlap conflicts

The goal of this project was to build a system that optimises train insertion while fully respecting these constraints.

## Key Functionalities

- models a fixed network of stations
- processes real timetable data
- evaluates feasible insertion paths
- detects and resolves conflicts
- ensures no disruption to existing services

## Approach

The system uses dynamic programming to evaluate the possible ways a new train can be inserted into the timetable. 
It handles edge cases and constraint conflicts by:

- structured logic
- systematic debugging
- real data-driven evaluation

## Documentation

Documentation and detailed explanation of the project logic are included in the thesis file.

## How to Use

1. Clone the repository  
2. Open the Python script  
3. Review the data input formats  
4. Run the script on test data  

---

## About Me

Computer Engineering graduate with a strong interest in system reliability, edge-case behaviour and logical consistency.

---

