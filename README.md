# Non-Invasive Glucose Estimation using Multi-Finger PPG

## Capstone Project - Department of Computer Engineering, Cebu Technological University - Main Campus

This repository contains the full project for the research paper, "A Comparative Analysis of Single-Finger and Multi-Finger Fusion for Non-Invasive Glucose Estimation with an Adapted LightGBM Model". This study investigates whether using photoplethysmography (PPG) signals from multiple fingers, processed with an advanced machine learning model, can provide more accurate and reliable non-invasive glucose estimations than traditional single-finger methods.

## Project Components

This project is organized into several key functional areas:

- **`01_Data_Collection_Tool/`**: Contains the Python data collection application and firmware for the ESP32 microcontroller.

- **`02_Machine_Learning_Mendeley/`**: Holds the machine learning pipeline used to train the baseline model on the public Mendeley PPG dataset.

- **`03_Hardware_Interface_Development/`**: Houses all hardware design aspects, including schematics, component lists, and assembly notes for the custom multi-finger PPG acquisition device.

- **`04_Collected_Data_Analysis/`**: Includes scripts for processing and analyzing the data collected from the custom system, including the multi-finger fusion analysis.


## General Workflow

1.  **Baseline Model Training**: Training a LightGBM machine learning model on a public single-finger PPG dataset to establish a performance benchmark.
2.  **Custom Data Collection**: Building a multi-finger PPG data acquisition system and collecting a new dataset.
3.  **Model Adaptation**: Fine-tuning the baseline model to work accurately with the new custom hardware, addressing a critical "domain shift" issue.
4. **Comparative Analysis**: Evaluating the adapted model's performance on single-finger signals versus fused multi-finger signals to identify the superior approach
