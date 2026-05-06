# ProResume Optimizer – Resume Evaluation and Improvement System

## Overview

ProResume Optimizer is a Python-based resume evaluation system developed using object-oriented design principles. The system analyzes resume content using rule-based logic and generates structured feedback related to resume quality, role alignment, ATS compatibility, measurable achievements, and weak phrasing.

The project was developed as part of Systems Analysis and Design coursework and demonstrates the use of UML modeling, modular architecture, controller-based processing, and evaluation reporting.

---

## Project Files

- `ProResumeOptimizer_Resume_Evaluationand_Improvement_System.ipynb`  
  Main source code notebook containing implementation, workflow execution, and unit tests.

- `ProResume Advisor - FinalPaper.docx`  
  Complete development paper including UML diagrams, system design, requirements, implementation details, testing, and conclusions.

---

## Features

- Resume preprocessing and section extraction
- Structure validation and completeness analysis
- Role-specific keyword matching
- ATS compatibility evaluation
- Weak phrasing detection
- Weighted score computation
- Structured evaluation report generation
- Resume re-submission and re-evaluation
- Unit testing of major components

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Regular Expressions (`re`)

---

## System Architecture

The project follows a modular layered architecture consisting of:

- Interface Layer
- Controller Layer
- Analysis Layer
- Model Layer
- Evaluation Layer
- Configuration Layer

The implementation includes analyzers such as:

- StructureAnalyzer
- RoleAlignmentAnalyzer
- ATSAnalyzer
- ScoringEngine
- ResumeEvaluationController

---

## How to Run

1. Install Python 3.x and Jupyter Notebook.

2. Install required dependency:

```bash
pip install numpy


Open the notebook file:
`ProResumeOptimizer_Resume_Evaluationand_Improvement_System.ipynb`

Run all notebook cells sequentially from top to bottom.

The notebook will:
- preprocess resume text
- perform structure analysis
- evaluate role alignment
- perform ATS evaluation
- compute final score
- generate evaluation feedback
- execute unit tests

All outputs will be displayed directly inside the notebook.
