# Railway Timetable Optimisation System

Python-based constraint optimisation system developed as part of my Bachelor’s thesis in Computer Engineering (Automation Systems).

The objective of this project was to insert an additional train into an existing real-world railway timetable without modifying the original schedule structure or disrupting operational stability.

---

## Technologies

- Python
- Pandas (data manipulation & time-based analysis)
- Dynamic Programming (constraint-based optimisation)

---

## Problem Context

The railway network included:

- Trains operating in both directions (up and down flows)
- Single-track sections shared by opposite flows
- Block Points used to regulate train separation and safety constraints
- Fixed station sequences
- Real operational timetable data
- Time overlap and resource conflicts

The main challenge was to determine whether a new train could be inserted without interfering with existing services, particularly across shared single-track segments and regulated block sections.

---

## System Logic

The solution:

- Models a fixed railway network with bidirectional flows
- Processes real timetable datasets (XML & JSON)
- Evaluates feasible insertion paths using dynamic programming
- Detects conflicts across single-track and block-regulated sections
- Ensures full non-interference with existing scheduled trains

The system required extensive debugging, structured logical modelling and careful constraint validation to maintain overall schedule consistency.

---

## Documentation

A complete technical explanation of the modelling approach, optimisation logic and dataset structure is included in the thesis document within this repository.
