## Drug Discovery Project

# Computational Drug Discovery Targeting HER2

This repository contains a computational drug discovery project focused on the Human Epidermal Growth Factor Receptor 2 (HER2, ERBB2). The project follows a structure-based drug discovery workflow inspired by the methodology demonstrated in the following tutorial:

https://www.youtube.com/watch?v=jBlTQjcKuaY&t=2413s

The objective of this work is to apply computational chemistry and bioinformatics techniques to identify and evaluate small-molecule candidates that may interact with HER2.

---

## Background

HER2 is a receptor tyrosine kinase that plays a critical role in cell growth and proliferation. Overexpression or amplification of the ERBB2 gene is associated with aggressive forms of cancer, particularly breast cancer. Due to its clinical relevance, HER2 has been extensively studied as a therapeutic target.

Computational approaches such as molecular docking and ligand screening provide a cost-effective method for prioritizing compounds prior to experimental validation.

---

## Project Objectives

The main goals of this project are to:

- Prepare and analyze the three-dimensional structure of the HER2 protein
- Generate and preprocess small-molecule ligand libraries
- Perform molecular docking to predict ligand–protein binding affinities
- Rank and analyze candidate compounds based on docking scores
- Visualize and interpret protein–ligand interactions

---

## Methods Overview

The workflow implemented in this repository includes the following steps:

1. Protein structure retrieval and preparation from the Protein Data Bank (PDB)
2. Ligand preparation and format conversion
3. Structure-based molecular docking
4. Post-docking analysis and visualization
5. Result interpretation and prioritization of candidates

---

## Software and Tools

This project makes use of the following software and libraries:

- Python
- RDKit for cheminformatics and molecular handling
- AutoDock Vina for molecular docking
- Open Babel for file format conversion
- NumPy and Pandas for data analysis
- Matplotlib for data visualization

---


