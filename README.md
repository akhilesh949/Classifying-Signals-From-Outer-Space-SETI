# Classifying-Signals-From-Outer-Space-SETI
Classifying Signals from Outer space using Dataset provided by Search For Extraterrestrial Intelligence (SETI)


This project is inspired by the SETI Institute Code Challenge held in 2017 (https://www.seti.org/machine-learning-search-extraterrestrial-intelligence-hackathon-code-challenge)

The *Allen telescope array* at Search For Extraterrestrial Intelligence (SETI) scans the night sky for radio signals from outer space that are very faint. The goal is to search for persistent signals. There are some unwanted signals as well, so this project is to help increase the efficiency of these nightly scans by enabling the detection system to classify these signals and overlook the unwanted radio frequency signals.

In the dataset, we have the one-hot encoded spectrogram images of these signals. A signal processing problem has been converted to an image classification problem by SETI. 

The following were the different types of signals recorded and available in the dataset:

labels = ["squiggle", "narrowband", "noise", "narrowbanddrd"]
The narrowband signals are the desired signals for the organization.
Please follow the jupyter notebook in this repository for the implementation

<img src  = "SETI.jpg" >
