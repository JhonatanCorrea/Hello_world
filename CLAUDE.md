# Hello_world

## Project Overview

This repository contains a Jupyter notebook (`Copia_de_s01.ipynb`) used as educational material for the **"Diplomado de Análisis de datos y Machine Learning en Python"** (Data Analysis and Machine Learning Diploma in Python) from the Universidad de Antioquia's Centro de Big Data (Facultad de Ciencias Exactas y Naturales — FCEN).

The notebook is designed to run in **Google Colab** and covers foundational Python programming concepts for data science students.

## Notebook Content

The notebook covers:

- **Session 1: Introduction to Python**
  - Google Colaboratory introduction
  - Python modules and imports
  - Variables and data types (int, float, bool, string)
  - Operators and comparisons
  - Strings, lists, tuples, and dictionaries
  - Indentation and code blocks
  - Control flow: if/elif/else
  - Loops: for and while, break and continue
  - Functions and classes
  - File I/O: reading/writing files, uploading/downloading in Colab
  - Google Drive integration (PyDrive)
  - GitHub basics

## Dependencies

The notebook uses the following Python libraries:

- `numpy` — numerical computing
- `math` — standard math functions (built-in)
- `google.colab` — Colab-specific file upload/download (Colab only)
- `pydrive` — Google Drive integration (Colab only)

> **Note:** `google.colab` and `pydrive` are specific to Google Colab and will not work in a standard local Jupyter environment.

## Running the Notebook

### Google Colab (recommended)
Open the notebook directly in Colab using the badge at the top of the notebook, or via:
```
https://colab.research.google.com/github/JhonatanCorrea/Hello_world/blob/main/Copia_de_s01.ipynb
```

### Local Jupyter
```bash
pip install jupyter numpy
jupyter notebook Copia_de_s01.ipynb
```

## Working with This Repo

- The notebook is in Spanish and targets beginner Python learners
- Cells with `google.colab` or `pydrive` imports will fail outside Colab — this is expected
- No test suite or linter is configured for this project
