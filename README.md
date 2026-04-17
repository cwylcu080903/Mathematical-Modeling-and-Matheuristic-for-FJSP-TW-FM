# Mathematical Modeling and Matheuristic for FJSP-TW-FM

This repository provides implementations for solving the **Flexible Job Shop Scheduling Problem with Time-Window-Based Fixed Maintenance (FJSP-TW-FM)**.

---

## 📁 Repository Structure
```
FJSP_WINDOWSPM_GITHUB/
├── dataset/ # Benchmark instances
│ ├── MFJS01.fjs
│ ├── MFJS02.fjs
│ ├── ...
│ ├── Mk01.fjs
│ ├── ...
│ └── Mk10.fjs
│
├── cp_model.py # Constraint Programming model for FJSP-TW-FM
├── ga_cp.py # GA-CP matheuristic algorithm
└── README.md
```

## 📊 Datasets

- **MFJS01–MFJS10**: Modified flexible job shop instances  
- **Mk01–Mk10**: Benchmark instances adapted with maintenance constraints  

Each `.fjs` file defines:

- Number of jobs and machines  
- Operation sequences  
- Alternative machines and processing times  

---

## ⚙️ Methods

### 1. Constraint Programming (CP)

- Implemented using `docplex.cp`
- Models:
  - Operation-machine assignment  
  - Precedence constraints  
  - Machine capacity constraints  
  - Maintenance time-window constraints  

---

### 2. GA-CP Matheuristic

- Hybrid algorithm combining:
  - Genetic Algorithm (GA) for global search  
  - Constraint Programming (CP) for solution refinement
 
## 📎 Code Availability

The associated manuscript is currently under peer review. The full implementation will be made publicly available upon acceptance.
