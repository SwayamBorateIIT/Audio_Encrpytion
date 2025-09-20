# EE323 Digital Signal Processing  
## Secure & Intelligent Speech Communication with Motion-Sensor Integration  

###  Project Overview  
This project develops a **Simulink-based Android application** that enables **secure speech communication** between two smartphones while simultaneously capturing and transmitting **motion-sensor data**.  

- **Phone A (Sender):**  
  - Records a voice signal using the device microphone.  
  - Encrypts the recorded voice using **Frequency Scrambling with Key-Based Permutation**, making it unintelligible to unauthorized users.  
  - Uses a **configurable encryption key** for both encryption and decryption.  
  - Captures **motion-sensor data (gyroscope & accelerometer)** simultaneously with the audio.  
  - Time-synchronizes motion data with the audio stream.  
  - Transmits both **encrypted audio** and **motion data** wirelessly to Phone B.  

- **Phone B (Receiver):**  
  - Receives the encrypted audio and motion data.  
  - Decrypts the audio using the same encryption key.  
  - Displays/logs the motion data in a **basic UI chart or log view** for analysis.  

---

###  Objectives  
- Develop a secure voice communication system using **Frequency Scrambling with Key-Based Permutation**.  
- Implement **wireless encrypted audio transmission** between two devices.  
- Integrate **motion-sensor data** (gyroscope + accelerometer) with audio communication.  
- Ensure **time-synchronization** between voice and motion data.  
- Design a **receiver-side interface** to decrypt, play, and analyze transmitted data.  

---

### Features  
- **Configurable Encryption/Decryption Key** for secure communication.  
- **Voice Recording** on Phone A with real-time encryption.  
- **Wireless Transmission** of encrypted audio + motion data.  
- **Motion Data Visualization** on Phone B.  
- **Time-Synchronized Data Streams** (voice + movement patterns).  

---

### Tools & Technologies  
- **Simulink** (MATLAB) for system modeling and Android integration.  
- **Android Devices** for sender (Phone A) & receiver (Phone B).  
- **Signal Processing**: Frequency Scrambling & Key-Based Permutation.  
- **Motion Sensors**: Gyroscope & Accelerometer APIs.  
- **Wireless Transmission Protocols**: TCP/IP or equivalent.  

---

### System Workflow  
1. **Sender (Phone A)**  
   - Record voice → Encrypt → Capture motion → Synchronize → Transmit.  

2. **Receiver (Phone B)**  
   - Receive encrypted data → Decrypt voice → Display motion data.  

---

### 👥 Contributors  
- **Course:** EE323 Digital Signal Processing  
- **Project Title:** Secure & Intelligent Speech Communication with Motion-Sensor Integration  

---
