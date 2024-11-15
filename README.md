# MSc-Thesis-Proposed-Product
A Deep Learning-Based Privacy Compliance Framework for IoT Applications

Thesis is attached too.

This repository contains a Python-based tool for analyzing IoT data, detecting threats, and checking compliance against various regulatory standards.

Features
Data loading and preprocessing from CSV files,
Training of Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) models for threat detection,
Compliance checking against regulatory standards (GDPR, CCPA, NIST),
Policy adjustment based on compliance results,
Interactive interface using IPython widgets,

Requirements
pandas,
numpy,
tensorflow,
scikit-learn,
python-docx,
matplotlib,
seaborn,
ipywidgets,

To install the required libraries, run:
bash
pip install pandas scikit-learn tensorflow python-docx ipywidgets matplotlib seaborn

Usage
Mount Google Drive (if using Google Colab),
Load and preprocess the data,
Train CNN and LSTM models,
Detect threats using trained models,
Check compliance against regulatory standards,
Adjust policies based on compliance results,
Enforce updated policies,

Main Components
Data loading and preprocessing,
Model training (CNN and LSTM),
Threat detection,
Compliance checking,
Policy adjustment and enforcement,
Interactive user interface,

File Structure
HomeC.csv: Input dataset,
Second IoT Dataset: RT_IoT2022,
Policies.docx: Initial policies document,
AdjustedPolicies.docx: Output file for adjusted policies,
