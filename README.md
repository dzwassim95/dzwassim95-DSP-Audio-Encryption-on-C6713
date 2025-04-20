# DSP Audio Encryption on TMS320C6713


<p align="center">
  <img src="assets/Block-diagram-for-Starter-Kit-TMS320C671-Taken-from-17.png" alt="Block Diagram" width="800"/>
</p>

<h2>📄 Project Overview</h2>

<p>
  This project presents the design and implementation of a basic audio encryption and decryption system using a Digital Signal Processor (DSP), specifically the Texas Instruments (TI) TMS320C6713. The system demonstrates simple, real-time encryption techniques suitable for the capabilities of this DSP platform. Instead of relying on complex cryptographic standards like AES or RSA, it employs lightweight methods such as:
</p>

<ul>
  <li>Pseudo-random key-stream generation with XOR operations</li>
  <li>Data permutation techniques</li>
</ul>

<p>The report covers:</p>
<ul>
  <li>An analysis of the TMS320C6713 architecture</li>
  <li>The associated Development Starter Kit (DSK)</li>
  <li>Development using Code Composer Studio</li>
  <li>Implementation of custom encryption methods</li>
  <li>Integration within a real-time audio processing pipeline</li>
  <li>Testing and verification approaches</li>
</ul>

<blockquote>
  <strong>⚠️ Note:</strong> The techniques used are not intended for high-security applications, but rather to demonstrate basic confidentiality and deter casual eavesdropping. The emphasis is on implementing low-overhead, real-time algorithms on embedded hardware.
</blockquote>

