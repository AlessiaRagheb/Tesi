# Railway Timetable Optimisation System

Python-based constraint optimisation system developed as part of my Bachelor’s thesis in Computer Engineering (Automation Systems).

The objective of this project is to insert an additional train into an existing real-world railway timetable without modifying the original schedule structure or disrupting operational stability.

---

## Technologies

- Python
- Pandas (data manipulation & time-based analysis)
- Dynamic Programming (constraint-based optimisation)

---

## Problem Context

Railway timetables involve multiple operational constraints, including:

- Bidirectional train flows
- Single-track sections
- Fixed station sequences
- Real operational data
- Temporal overlap conflicts

The challenge was to determine whether a new train could be inserted into the system while fully respecting these constraints.

---

## System Logic

The solution:

- Models a fixed railway network
- Processes real timetable datasets (XML & JSON)
- Evaluates feasible insertion paths using dynamic programming
- Detects scheduling conflicts and constraint violations
- Ensures non-interference with existing services

The system required extensive debugging and structured logical modelling to maintain consistency across all operational constraints.

---

## Documentation

A complete technical explanation of the modelling approach, optimisation logic and dataset structure is included in the thesis document within this repository.
