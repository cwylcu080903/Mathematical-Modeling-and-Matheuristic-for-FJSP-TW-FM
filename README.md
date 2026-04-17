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

- **MFJS01–MFJS10**  
- **Mk01–Mk10** 

Each `.fjs` file defines:

- Number of jobs and machines  
- Operation sequences  
- Alternative machines and processing times  

---

## ⚙️ Methods

### 1. CP model
### 2. GA-CP

 
## 📎 Code Availability

The associated manuscript is currently under peer review. The full implementation will be made publicly available upon acceptance.
