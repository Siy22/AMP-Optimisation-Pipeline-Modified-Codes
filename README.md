# AMP Optimisation Pipeline — Modified Code

> **Final Year Project:** *In Silico* AMP Optimisation and Discovery Pipeline

This repository contains all modified and custom code developed as part of a Research Project, focused on the computational screening, mutation, optimisation, and validation of antimicrobial peptides (AMPs).


## 📌 Project Overview

This repository stores code modifications made to run the pipeline on **Apple Silicon (M1 MacBook Air)** using VS Code. The pipeline integrates several open-source tools for AMP screening, classification, mutation, optimisation,generating and validation.


## 📁 Repository Contents

| Folder / File | Description |
|---|---|
| `modifiedversion/EvoGradient/` | Modified version of EvoGradient (adapted for MPS) |
| `modifiedversion/PyAMPA/` | Modified PyAMPA scripts for project compatibility |


## 🔧 Modifications Made

- Adapted **EvoGradient** from CUDA to **Metal Performance Shaders (MPS)** for M1 compatibility
- Resolved **PyTorch version conflicts**
- Modified **file input/output handling** in PyAMPA


## 📦 Original Tools & Licenses

This project uses modified versions of the following open-source tools:

| Tool | Source |
|---|---|
| EvoGradient | https://github.com/MicroResearchLab/AMP-potency-prediction-EvoGradient.git |
| PyAMPA | https://github.com/SysBioUAB/PyAMPA.git |

> All original copyright and license notices have been retained in their respective files. Modifications were made solely for **research and compatibility purposes**.


## 📄 License

This repository is released under the **MIT License**.

However, the **original tools retain their respective licenses**. Please refer to the original repositories for full licensing details.


## 🚀 How to Use

Detailed installation and usage instructions are available in the **individual folders**.

---

*Developed as part of a Final Year Project. For questions or clarifications, please open an issue or contact the repository owner.*
