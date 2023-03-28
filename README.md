# ETF Analysis

This repository houses code for a program to analyze a hypothetical fintech exchange-traded fund (ETF). The code in this repository houses a financial database and web application using SQL, Python, and the Voila library. 

The program, titled "etf_analyzer.ipynb", analyzes a single asset performance as well as the full portfolio performance over a 4 year period. Statistics are gathered and visuals are created to help digest the data.

---

## Technologies

This program use Python version 3.9.13 (which includes NumPy and Pandas). Additional packages used are HVPlot and SQLAlchemy.

---

## Installation Guide

To check your current Python version, run the following code in your terminal:   
python --version  

To check your installed packages, run one of the following lines of code in your terminal:  
pip list  
conda list  

If installation of the aforementioned packages is required, run the following code:  
conda instal pandas  
conda install -c pyviz holoviz  
conda install -c anaconda sqlalchemy  

---

## Usage

Important: This program is intended purely for academic purposes, and is solely an example of what is possible. This program is not intended to provide actual investment advice. 

To begin using this program, please download the following files (included in this repository) to your local machine:  
etf_analyzer.ipynb  
etf.db   

Running the first cell will import Pandas, NumPy, HVPlot, and SQLAlchemy. The first cell will also create a temporary SQLite database and an engine to interact with the SQLite database. Process to run the following cells to pull asset analysis, portfolio analysis, and the pertinent visuals.

---

## Contributors

Shahrukh Alam

---

## License

Columbia Enginerring: FinTech Bootcamp