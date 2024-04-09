# Anomaly-Detection-with-GESD
Project aiming to detect Statistical Anomalies within in-process data produced during the Additive Manufacture of Ti-6Al-4V using the GESD algorithm!

3D printing is becoming increasingly popular for producing medical components, as it lets you tailor the bone implant to the patients physiology. As this technology becomes more popular, improving the process by detecting defects will become vital. To this end, this project aimed to detect a mechanical defect, within the component, through the analysis of in-process data using the Generalised Extreme Studentized Deviate (GESD) test. 

This test is an iterative form of the Grubbs Anomaly detection test, and cycles through the data a set number of times, until anomalies are no longer present. No packages that implemented this model were known, so the test was written as a function built on prewritten functions. Preprocessing of the signals to remove noise was also required, with simple centered/non-centered rolling averages analysed, as well as Savitsky Golay interpolation. 

The number of detected anomalies vs signal processing method was analysed here, as well as comparison of statistical results against known defective layers. 

Models used: GESD, 

Packages used: Pandas, Numpy, Matplotlib, SciPy, ntpath



