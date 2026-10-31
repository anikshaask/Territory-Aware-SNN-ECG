 # Territory-Aware Spiking Neural Network for Explaining Myocardial Infarction Localization and Baseline Relative Ischemia Monitoring using 12-Lead ECG

## Project Description

The objective of this project is to create a Territory-Aware Spiking Neural Network to identify and explain the location of Myocardial Infarctions (MI) and monitor ischemia relative to baseline using 12-Lead Electrocardiogram (ECG) signals.
This project will aim to analyse ECG signals to identify patterns of MI's and create an explainable output.

## Objectives

Analyse 12-lead ECG signals
Preprocess the ECG signals
Create a Spiking Neural Network to classify ECG signals
Identify locations of MI based on cardiac territories
Monitor ischemia based on baseline patterns
Create an explainable output

## Technologies

Python
Google Colab
NumPy
Pandas
Matplotlib
Scikit-learn
Spiking Neural Network

## Dataset

Dataset: PTB-XL v1.0.3 (Wagner et al., Scientific Data 2020) — 21,799 10-s 12-lead ECGs from 18,869 patients, free on PhysioNet.

Dataset Source: https://physionet.org/content/ptb-xl/1.0.3/
The ECG dataset is used to help preprocess the data, analyse features, create and evaluate the model.

## Methodology

Collect and load dataset
Preprocess ECG signals
Clean data
Extract features
Implement territory-aware SNN
Identify locations of MI
Monitor ischemia relative to baseline
Evaluate model

## Preprocessing

Preprocessing is done to prepare the ECG signals.
Preprocessing steps can be seen in the project notebook.

## Results

Experimental outputs with graphs and visualisations can be found in the Results folder.

## Repository Layout

Territory-Aware-SNN-ECG/

├── Dataset/

├── Preprocessing/

├── Implementation/

├── Results/

├── README.md

└── requirements.txt

## Implementation

The complete project implementation, including data preprocessing and experimental outputs, is available in Google Colab.

Colab Notebook: https://colab.research.google.com/drive/1OrIInB388r0NcuKnc-suQ-a8geS-80Qk#scrollTo=18d94a4d

## Conclusion

This project looked into using territory-aware spiking neural networks to explain the location of myocardial infarctions and monitor ischemia relative to baseline using 12-Lead ECG signals.

## Team Members

S K Anikshaa
Janani A
Dhibish B 

## References

## References

1. P. Wagner et al., "PTB-XL, a large publicly available electrocardiography dataset," Scientific Data, vol. 7, Art. 154, 2020.

2. A. L. Goldberger et al., "PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals," Circulation, vol. 101, no. 23, pp. e215-e220, 2000.

3. E. O. Neftci, H. Mostafa, and F. Zenke, "Surrogate Gradient Learning in Spiking Neural Networks," IEEE Signal Processing Magazine, vol. 36, no. 6, pp. 51-63, 2019.

4. Additional research references are provided in the project paper.
