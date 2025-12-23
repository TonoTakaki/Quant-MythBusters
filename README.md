# Quant-MythBusters

> *“In theory, theory and practice are the same.  
> In practice, they are not.”*

This repository is a **systematic replication lab for quantitative finance and asset pricing papers**, with an emphasis on **reproducibility, clean implementation, and empirical rigor**.

The goal is not to chase SOTA results, but to **understand what actually works, why it works, and when it breaks**.

---

## 📌 Scope & Philosophy

This project focuses on **end-to-end replication** of influential and representative papers in quantitative finance, including:

- Asset pricing & factor models  
- Cross-sectional return prediction  
- Market microstructure & high-frequency data  
- Machine learning methods in finance  
- Portfolio construction & risk modeling  

**Core principles**:
- 📐 Faithful to the original paper
- 🧪 Reproducible experiments
- 🔍 Transparent assumptions
- ⚠️ Explicit limitations

---

## 📂 Repository Structure

```text
quant-myth-busters/
│
├── papers/                 # Paper-specific implementations
│   ├── paper_name_1/
│   │   ├── README.md        # Paper summary & replication notes
│   │   ├── data/            # Raw / processed data
│   │   ├── src*/             # Core implementation（if necessary)
│   │   ├── experiments/     # Reproduction of tables & figures
│   │   └── results/         # Outputs & diagnostics
│   │
│   └── paper_name_2/
│
├── common/                 # Shared utilities
│   ├── data_utils.py
│   ├── metrics.py
│   └── backtesting.py
│
├── environment/            # Reproducible environments
│   ├── requirements.txt
│   └── environment.yml
│
└── README.md

