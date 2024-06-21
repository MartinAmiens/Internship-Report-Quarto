# Internship Report

Welcome to the repository for my internship report, produced with Quarto on RStudio. This repository contains all the files needed to reproduce and view the report.

## Structure of the repository

-   'index.qmd': Main file of the dissertation, including the text, analyses and visualisations.
-   '\_quarto.yml': Quarto configuration file defining the global parameters of the project.
-   '\_output.yml': Configuration file for rendering options.
-   'data/': Folder containing the datasets used in the analyses.
    -   'data_raw.csv': Raw data.
    -   'data_cleaned.csv': Cleaned data ready for use.
-   'R/': R scripts used for analysis and visualisation.
-   'analysis.R': Main script containing the analyses.
-   'plot_functions.R': Functions for creating graphs.
-   'figures/': Folder containing the figures generated for the dissertation.
-   'bibliography/': Bibliographic reference files.
-   'references.bib': BibTeX file containing bibliographic references.
-   'styles/': Folder containing style files (CSS, LaTeX files, etc.).
-   'output/': Folder containing rendered versions of the dissertation (PDF, HTML, etc.).

# Instructions for reproducing the report

## Clone the repository :

git clone https://github.com/MartinAmiens/Internship-Report-Quarto.git

cd Internship-Report-Quarto

## Installing dependencies :

Make sure you have R and RStudio installed, as well as the necessary packages. You can use the install_packages.R file to install the required packages.

source('install_packages.R')

## Open the project in RStudio :

Open the file Internship-Report-Quarto.Rproj in RStudio.

## Render the document :

Use Quarto to render the document in the desired format.

quarto::quarto_render(input = "index.qmd", output_format = "pdf")

# Notes

Please check that all file paths in the project are correct and appropriate for your working environment. Analyses and visualisations can be modified in R scripts as required.

# Writing instructions

Please open the file **Guide_stage_M1_BIBS_2023-24.pdf** to read the writing instructions.
