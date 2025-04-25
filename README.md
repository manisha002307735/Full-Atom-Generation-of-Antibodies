**Antibody CDR Modeling Project**
This repository contains code and documentation for the project "Computational Modeling and Structural Analysis of Antibody CDR Regions". The aim of this project is to analyze and simulate the structural diversity of antibody Complementarity-Determining Regions (CDRs) using statistical and geometric methods.

**Project Structure**
.
├── data/                   # Raw dataset (CDR sequences from OAS)
├── notebooks/             # Jupyter notebooks for analysis and visualization
├── outputs/               # Generated visualizations and results
├── ProjectReport_Group.pdf
├── Full-Atom Generation of Antibodies.ipynb
└── README.md              # This file

**Dependencies**
To reproduce results, use the following setup:

Python 3.10+

Libraries:

numpy

pandas

matplotlib

seaborn

ipywidgets (optional for interactivity)


You can install them using:

pip install -r requirements.txt

**Setup Instructions**
1. Clone the repository:
git clone <repository-url>
cd antibody-cdr-modeling

2. Install dependencies:
pip install -r requirements.txt

3. Run Notebooks: Open Full-Atom Generation of Antibodies.ipynb in Jupyter Notebook and run all cells to generate figures, statistics, and visualizations.

**Dataset**
Source: Observed Antibody Space (OAS)

19,839 annotated antibody sequences with both nucleotide and amino acid CDR information.

