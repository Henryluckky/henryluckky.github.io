---
title: Real-time Biosignal Recording and Machine-Learning Analysis System
collection: publications
permalink: /publication/AICAS
excerpt:
date: March. 2022
venue: 'IEEE AICAS'
paperurl: 'http://henryluckky.github.io/files/Intelligent_Real_time_Electrophysiological_Signal_Processing_System_based_on_FPGA_acceleration (1).pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Biosignal recording and processing systems (BRPSs) are in high demand for numerous applications such as brainmachine interfaces, healthcare, and other clinical applications. However, conventional BRPS can only perform simple operations, such as filtering and denoising, but cannot perform robust machine learning-based analyses in real time. This paper proposes an intelligent BRPS that consists of a signal recording frontend for biosignal acquisition, control and visualization hub, and FPGA board for machine learning acceleration. High-speed Ethernet and PCIe interfaces were used to increase the data transmission rate of the system. Moreover, the integrated accelerator in the FPGA is designed in a single-instruction-multiple-data (SIMD) mode to perform complex machine learning operations in
parallel to speed up data-processing tasks. The proposed system is validated for various applications, including EEG-based seizure
prediction with a convolutional neural network (CNN), EMGbased gesture recognition with a spiking neural network (SNN), and ECG-based arrhythmia detection with a binary neural network (BNN). Experimental results reveal that this system takes 13 ms to process one-second electrophysiological signals at 512 Hz and 32 channels, thus achieving real-time performance. The proposed BRPS is an open-source and expandable system, and different machine-learning approaches can be configured for diverse applications.
[Our poster](/images/AICAS_poster.png)



<!-- [http://epub.cnipa.gov.cn/certifdesc.action?strWhere=CN213138832U](http://henryluckky.github.io/files/Intelligent_Real_time_Electrophysiological_Signal_Processing_System_based_on_FPGA_acceleration (1).pdf) -->