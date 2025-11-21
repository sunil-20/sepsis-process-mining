# Sepsis Process Mining (Healthcare Event Log Analysis)

This project analyzes a real hospital event log of sepsis patient cases using Python and PM4Py. 
The goal is to understand patient flow, measure cycle times, and identify potential bottlenecks 
in the clinical workflow.

## Dataset
The dataset used is the **Sepsis Cases – Event Log** published by Eindhoven University of Technology (TU/e).  
It contains ~1,050 patient traces with timestamps, diagnostic attributes, lab results, and clinical activities.

## Objectives
- Load and parse the XES event log using PM4Py  
- Convert the log into a pandas DataFrame  
- Sort events by patient and timestamp  
- Compute cycle time metrics per patient  
- Identify delays and bottlenecks in the clinical pathway  
- Explore diagnostic attributes (CRP, Lactic Acid, etc.)

## Tools & Libraries
- Python  
- PM4Py  
- Pandas  
- VS Code  

## How to Run
1. Create a virtual environment  
2. Install dependencies:
```
pip install pm4py pandas
```
3. Run:

## Why This Project?
Sepsis requires rapid diagnosis and treatment. Understanding delays in lab tests and intervention 
timing can help improve emergency department workflows and patient outcomes. This project demonstrates 
how process mining techniques can support healthcare operations and clinical decision improvement.
