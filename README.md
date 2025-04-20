<<<<<<< HEAD
<p align="center">
  <img src="assets/block_diagram.png" alt="Block Diagram" width="800"/>
</p>

# DSP Audio Encryption on TMS320C6713

This report details the design and implementation considerations for a simple Digital Signal Processor (DSP)–based audio encryption and decryption system utilizing the Texas Instruments (TI) TMS320C6713 device. The primary objective is to explore basic techniques suitable for real-time execution on this specific DSP platform, focusing on methods like pseudo-random key-stream generation with XOR operations and data permutation, rather than computationally intensive, standardized cryptographic algorithms (e.g., AES, RSA). The scope encompasses an analysis of the TMS320C6713 architecture, its associated Development Starter Kit (DSK), the development environment (Code Composer Studio), selection and implementation of simple encryption algorithms, integration into a real-time audio processing framework, and methods for testing and verification. It is crucial to emphasize that the encryption techniques discussed herein are intended for basic confidentiality or deterring casual eavesdropping, not for providing robust security against determined adversaries. The focus remains on the practical aspects of implementing computationally lightweight algorithms within the real-time constraints imposed by audio signal processing on the target hardware. 
=======
# DSP Audio Encryption on TMS320C6713

<p align="center">
  <img src="https://www.researchgate.net/publication/258669537/figure/fig2/AS:324340324290561@1454340167219/Block-diagram-for-Starter-Kit-TMS320C671-Taken-from-17.png" alt="Project Banner" width="800"/>
</p>


This report details the design and implementation considerations for a simple Digital
Signal Processor (DSP)–based audio encryption and decryption system utilizing the Texas
Instruments (TI) TMS320C6713 device. The primary objective is to explore basic techniques
suitable for real-time execution on this specific DSP platform, focusing on methods like
pseudo-random key-stream generation with XOR operations and data permutation, rather
than computationally intensive, standardized cryptographic algorithms (e.g., AES, RSA).
The scope encompasses an analysis of the TMS320C6713 architecture, its associated
Development Starter Kit (DSK), the development environment (Code Composer Studio),
selection and implementation of simple encryption algorithms, integration into a real-time
audio processing framework, and methods for testing and verification.
It is crucial to emphasize that the encryption techniques discussed herein are intended
for basic confidentiality or deterring casual eavesdropping, not for providing robust security
against determined adversaries. The focus remains on the practical aspects of implementing
computationally lightweight algorithms within the real-time constraints imposed by audio
signal processing on the target hardware.
>>>>>>> 047cb49117708629c8fd8e7ef545a8134888780c
