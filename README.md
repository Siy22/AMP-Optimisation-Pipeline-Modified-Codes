AMP Optimisation Pipeline - Modified Code
This repository contains all the modified and custom code used in my Final Year Project: In Silico AMP Optimisation and Discovery Pipeline.
Project Overview
This repository stores the code modifications made to run the pipeline on Apple Silicon (M1 MacBook Air) using VS Code. The pipeline integrates several open-source tools for antimicrobial peptide (AMP) screening, mutation, optimisation, and validation.
Repository Contents

modified_evoGradient/ – Modified version of EvoGradient (adapted for MPS)
modified_pyAMPA/     – Modified PyAMPA scripts for project compatibility
custom_AMPAnalyse/   – Custom fitness-based script developed for this project
Other supporting scripts

Modifications Made

Adapted EvoGradient from CUDA to Metal Performance Shaders (MPS) for M1 compatibility
Resolved PyTorch version conflicts
Modified file input/output handling in PyAMPA
Created AMPAnalyse tool to bridge optimisation and safety cycles

Original Tools & Licenses
This project uses modified versions of the following open-source tools:

EvoGradient → https://github.com/MicroResearchLab/AMP-potency-prediction-EvoGradient.git
PyAMPA → [[Original Link]](https://github.com/SysBioUAB/PyAMPA.git)


All original copyright and license notices have been retained in the respective files. Modifications were made solely for research and compatibility purposes.
License
This repository is released under the MIT License.
However, the original tools retain their respective licenses. Please refer to the original repositories for full licensing details.
How to Use
Detailed installation and usage instructions are available in the individual folders.
