# Low-Level-Differential-Diagnostic-System
A rule-based clinical decision support demo built with Python, SQLAlchemy, and Jupyter Notebook. Loads a JSON symptom database into SQLite, applies a scoring formula (Frequency × Evoking Strength), and returns the top probable diagnoses in descending order.
# Low-Level Clinical Differential Diagnosis System (Educational)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AsianaHolloway/Low-Level-Differential-Diagnostic-System/blob/main/AssignmentDiffrentialDiagnostics.ipynb)


A simplified **clinical decision support system** using **Python, SQLAlchemy, and Jupyter Notebook**.  
Loads a JSON symptom database into **SQLite**, applies the scoring formula:

> **Score = Frequency × EvokingStrength**

and returns the top-N probable diagnoses in descending order.

⚠️ *Educational demo only — not a clinical tool.*

---

## Key Features
- JSON → **SQLAlchemy ORM** → **SQLite** pipeline  
- Many-to-many mapping (symptoms ↔ conditions)  
- Transparent rule-based scoring (no ML “black box”)  
- Outputs top-N probable diagnoses for patient symptoms  

---

## Quick Start (Colab)
Click the badge to run in the cloud (no install):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AsianaHolloway/Low-Level-Differential-Diagnostic-System/blob/main/AssignmentDiffrentialDiagnostics.ipynb)


---

## Example Output

Input symptoms:  
`["Fever", "Cough", "Headache", "Shortness of Breath"]`

### Screenshot
![Example Output](https://github.com/AsianaHolloway/AssignmentDifferentialDiagnostics/blob/main/images.png?raw=true)

## Project Purpose
This project demonstrates how a simple **rule-based clinical decision support system** can be built by combining structured data, databases, and algorithmic scoring. The goal was to replicate the workflow of mapping symptoms to conditions and producing ranked outputs — similar to how decision support modules in EHR systems work.

## What I Learned
- How to design and query a **many-to-many schema** using SQLAlchemy and SQLite  
- How to transform JSON clinical data into a normalized relational structure  
- How to implement and test a **rule-based scoring function** (Frequency × EvokingStrength)  
- How to present results in **Pandas DataFrames** and visualize outputs for interpretation  

## Real-World Applications
- Shows transferable skills in **data modeling**, **database management**, and **algorithm design**  
- Reflects how informatics professionals build **clinical decision support (CDS) prototypes**  
- Demonstrates practical use of **Python + SQL** for healthcare data workflows




