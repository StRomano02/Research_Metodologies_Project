# 📘 Privacy and Utility in Tabular Data: A Systematic Evaluation of Privacy-Preserving Techniques

This project investigates multiple techniques for **synthetic data
generation** and **privacy preservation**, evaluating how each method
affects both data utility and the protection of sensitive information.\
The goal is to compare traditional approaches and modern
deep-learning--based methods, understanding the trade-off between
**realism**, **model performance**, and **privacy guarantees**.

## 📁 Project Structure

The project is organized into a series of Jupyter notebooks, each
focusing on a specific stage or technique:

### **01 -- Data Preprocessing & EDA**

Initial data cleaning, preprocessing, and exploratory data analysis.\
Defines the baseline metrics used throughout the project.

### **02 -- Real Baseline**

Machine learning models trained on the original dataset to establish a
benchmark.\
All synthetic approaches are compared against this reference.

### **03 -- Synthetic Baseline (CTGAN)**

Synthetic data generation using **CTGAN**.\
Includes model training and initial evaluations (statistical similarity
and downstream task performance).

### **04 -- k-Anonymity Extension**

Implementation of **k-anonymity--based** methods to anonymize the
dataset and reduce re-identification risk.

### **05 -- Diffusion Models**

Use of **diffusion models** to generate high-quality synthetic data.\
Explores strengths and limitations compared to GAN-based methods.

### **06 -- Noise Perturbation**

Application of controlled noise to real data as a privacy mechanism.\
Different noise intensities are tested and analyzed.

### **07 -- Overall Comparison**

A full comparative analysis of all methods, evaluating: - Data quality\
- Statistical similarity\
- Performance of ML models trained on each dataset\
- Achieved privacy levels

## Final Outcome

This project provides a comprehensive understanding of how various
synthetic data and privacy-preserving methods perform in practice.\
The final notebook consolidates and compares all results to highlight
strengths, weaknesses, and the best trade-offs.

## Authors
- **Emanuele Minotti** 
- **Stefano Romano** 

## Course
**Research Methodologies and Scientific Writing**  

## University
**Kungliga Tekniska Högskolan**  
