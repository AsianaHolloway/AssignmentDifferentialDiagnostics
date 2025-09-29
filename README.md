# Low-Level-Differential-Diagnostic-System
A rule-based clinical decision support demo built with Python, SQLAlchemy, and Jupyter Notebook. Loads a JSON symptom database into SQLite, applies a scoring formula (Frequency × Evoking Strength), and returns the top probable diagnoses in descending order.
# Low-Level Clinical Differential Diagnosis System (Educational)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AsianaHolloway/Low-Level-Differential-Diagnostic-System/blob/main/AssignmentDifferentialDiagnostics.ipynb)

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

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AsianaHolloway/Low-Level-Differential-Diagnostic-System/blob/main/AssignmentDifferentialDiagnostics.ipynb)

---

## Run Locally

Clone the project:

```bash
git clone https://github.com/AsianaHolloway/Low-Level-Differential-Diagnostic-System.git
cd Low-Level-Differential-Diagnostic-System

Install dependencies:
pip install -r requirements.txt

Launch Jupyter Notebook:
jupyter notebook AssignmentDifferentialDiagnostics.ipynb


