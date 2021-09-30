# Automatic-Modulation-Classification-with-Deep-Learning
Using the multi-class modulation dataset Tensorflow library with different SNR levels, different CNN models were trained with the GPU and the modulation types were classified for each SNR level.


## What is Modulation?
Modulation is a method that can carry a low frequency information signal to a long distance with a high frequency carrier signal. There are different modulation types under the two basic methods, analog and digital. Two signals are needed to perform the modulation process. These signals are; Information Signal and Carrier Signal. The low frequency information signal is called modulating, modulating, modulating signal, signal to be sent or low frequency signal. The high frequency carrier signal is called the modulating RF (Radio Frequency) signal or porter signal. In the modulation process, the modulating signal is the information signal; The modulated or modulated signal is the carrier signal.

### Modulation Types and Features

At the end of the modulation process, the frequency, amplitude and phase of the carrier signal are changed. In general, there are three types of modulation.

a) Amplitude Modulation (A-M): It is defined as changing the amplitude of the carrier signal depending on the amplitude and frequency of the information signal.

b) Frequency Modulation (F-M): It is the change of the carrier signal frequency depending on the frequency and amplitude of the information signal.

c) Phase Modulation (P-M): It is expressed as the change of the carrier signal phase depending on the frequency and amplitude of the information signal. Also known as Indirect F-M.

The automatic modulation classification (AMC) process is a method used to classify modulation types from the received signal. Automatic modulation classification is used in a significant part of various military and civilian communication systems such as electronic warfare, software-based radio and spectrum awareness. In this study, using deep learning models, the method of Deep Learning-based Automatic Modulation Systems is classified for different SNR values ​​and the performances of the models used in the modulation classification problem are compared.

# Dataset 
Radio ML 2016.a Dataset
It was decided to use the RadioML 2016.a data set, which was also used in the article “Robust and Fast Automatic Modulation Classification with CNN under Multipath Fading Channels”, which was used as a reference while carrying out this project.
RadioML 2016.a is a synthetic dataset created with GNU Radio, consisting of 11 modulations (8 digital and 3 analog) at varying signal-to-noise ratios.
Each modulation here consists of 20000 pieces of data, each modulation has 20 different SNR levels between -20db and 18db with 2db intervals. There are 1000 pieces of data in each SNR level.
The shape of the dataset is (220000, 2, 128 ). There are 220000 pieces of data in total. Each data contains 2x128 information as two axes, real and imaginary axis.

![image](https://user-images.githubusercontent.com/62508669/135423929-b1b5843d-8dd3-443f-b0d2-cb5ce699d8dc.png = 250x250) 

