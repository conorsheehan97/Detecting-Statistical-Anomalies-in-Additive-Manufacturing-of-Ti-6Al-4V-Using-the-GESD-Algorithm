# Detecting Statistical Anomalies in Additive Manufacturing of Ti-6Al-4V Using the GESD Algorithm
## Overview
This project aims to detect statistical anomalies within in-process data produced during the additive manufacture of Ti-6Al-4V using the Generalized Extreme Studentized Deviate (GESD) algorithm. With the growing popularity of 3D printing for producing medical components tailored to patients' physiology, improving the manufacturing process by detecting defects is vital.

## Purpose
The goal is to detect mechanical defects in components through the analysis of in-process data using the GESD test. The GESD algorithm is an iterative form of the Grubbs anomaly detection test, cycling through data until anomalies are no longer present. Due to the lack of available packages implementing this model, the GESD test was written as a custom function built on prewritten functions.

## Methodology
### Preprocessing:
 - Noise removal from signals using centered/non-centered rolling averages and Savitzky-Golay interpolation.
### Anomaly Detection:
 - Implementation of the GESD test to identify statistical anomalies.
### Analysis:
 - Evaluation of the number of detected anomalies against different signal processing methods.
 - Comparison of statistical results against known defective layers.
### Models Used
 - Generalized Extreme Studentized Deviate (GESD)
### Packages Used
 - Pandas
 - Numpy
 - Matplotlib
 - SciPy
 - ntpath

## Conclusion
This project demonstrates the application of the GESD algorithm to detect mechanical defects in 3D printed components. By preprocessing in-process data and applying the GESD test, we were able to identify statistical anomalies that correlate with known defective layers. The methods and models developed here can be applied to other manufacturing processes to improve defect detection and quality control.

We invite contributions and feedback to further refine and enhance this project. Thank you for exploring this work, and we hope it provides valuable insights and tools for your own endeavors in manufacturing and anomaly detection.
