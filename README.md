# Quantum-Enhanced Security for IoT/IoV in 6G Networks

## 📌 Project Overview
This project demonstrates a practical implementation of **quantum-enhanced security and intelligence** for Internet of Things (IoT) and Internet of Vehicles (IoV) systems in **future 6G networks**.  

It addresses three critical challenges of next-generation networks:  

- ⚡ **Data Overload** – Massive sensor data streams  
- 🔋 **Resource Constraints** – Power-limited IoT devices  
- 🔐 **Quantum-Era Security Threats** – Breaking of classical encryption by quantum computers  

The implementation provides a **proof-of-concept** showcasing:  

- ✅ Simulation of IoT sensor data streams  
- ✅ Classical anomaly detection using Principal Component Analysis (PCA)  
- ✅ Quantum-safe cryptographic key exchange using post-quantum algorithms  

---

## 🧠 Conceptual Framework

### The Problem: 6G, IoT, and IoV Challenges
Imagine a futuristic city's nervous system:  

- **IoT Devices** → Nerve endings (sensors, smart devices)  
- **IoV Systems** → Fast-twitch nerves (vehicles, traffic systems)  
- **6G Network** → Spinal cord & brain (ultra-low latency, massive throughput)  

**Core Challenges:**  
1. **Data Overload** – Terabytes of data causing "sensory overload"  
2. **Resource Constraints** – IoT devices lack processing capacity  
3. **Security Threats** – Quantum computers can break today’s encryption  

### The Quantum Solution
This project demonstrates two approaches:  

- **Quantum-Inspired Algorithms** → PCA for anomaly detection (simulating Quantum PCA benefits)  
- **Quantum-Safe Cryptography** → Post-quantum cryptographic algorithms resistant to quantum attacks  

---

## 📂 Project Structure
```
├── iot_simulator.py          # Simulates IoT sensor data stream
├── anomaly_detector.py       # PCA-based anomaly detection
├── quantum_safe_crypto.py    # Quantum-safe key exchange implementation
├── iot_data_stream.csv       # Generated sensor data (from simulator)
├── pca_anomaly_detection.png # Visualization of detection results
└── requirements.txt          # Python dependencies
```

---

## ⚙️ Implementation Details

### 1. IoT Data Simulation (`iot_simulator.py`)
- Generates synthetic sensor data (temperature & humidity)  
- 1000 normal readings: **25°C ± 2°**, **50% ± 5% humidity**  
- 50 anomalous readings: **60°C spikes**  
- Outputs to `iot_data_stream.csv`  

### 2. Classical Anomaly Detection (`anomaly_detector.py`)
- PCA-based anomaly detection  
- Identifies outliers based on distance from data center  
- Visualizes **normal vs anomalous points**  
- Demonstrates **pattern recognition** similar to **Quantum PCA**  

### 3. Quantum-Safe Cryptography (`quantum_safe_crypto.py`)
- Implements **post-quantum key exchange** using **Dilithium2**  
- Simulates **two IoT devices establishing secure communication**  
- Uses **KEM (Key Encapsulation Mechanism)**  
- Resistant to **quantum computer attacks**  

---

## 🔧 Installation & Requirements
```bash
# Clone the repository
git clone https://github.com/umarnabibhat/Quantum-Enhanced-Security-for-IoT-IoV-in-6G-Networks
cd quantum-iot-6g

# Install dependencies
pip install -r requirements.txt

# Or install manually
pip install numpy pandas scikit-learn matplotlib oqs
```

---

## 🚀 Usage

### 1. Generate IoT Data Stream
```bash
python iot_simulator.py
```

### 2. Detect Anomalies
```bash
python anomaly_detector.py
```

### 3. Test Quantum-Safe Cryptography
```bash
python quantum_safe_crypto.py
```

---

## 📊 Results
After running the complete pipeline:  

- `iot_data_stream.csv` → Simulated IoT data with anomalies  
- `pca_anomaly_detection.png` → Visualization of anomalies  
- Terminal output → Successful **quantum-safe key exchange**  

---

## 🔍 Technical Insights
- **Quantum Advantage**  
  - QPCA offers exponential speedup compared to classical PCA  
  - Post-quantum algorithms resist both classical & quantum attacks  

- **Real-World Applications**  
  - 🏙️ Smart Cities → Detecting failures & cyberattacks in real time  
  - 🚗 Connected Vehicles → Securing V2V communication  
  - 🏭 Industrial IoT → Protecting infrastructure with quantum-resistant security  

---

## 🛠️ Future Enhancements
- ✅ Integrate with **quantum hardware** (Qiskit, Cirq)  
- ✅ Add more **post-quantum schemes** (Kyber, Falcon)  
- ✅ Real-time **streaming anomaly detection**  
- ✅ Performance benchmarking of classical vs quantum approaches  

---

## 📚 References & Learning Resources
- [NIST Post-Quantum Cryptography Standardization](https://csrc.nist.gov/projects/post-quantum-cryptography)  
- [Qiskit Textbook – Quantum Machine Learning](https://qiskit.org/textbook)  
- [Open Quantum Safe Project](https://openquantumsafe.org/)  

---

## 🤝 Contributing
This project is an **educational demonstration** of quantum-enhanced technologies for 6G networks.  
Contributions, improvements, and extensions are welcome!  

---

## 📜 License
This project is provided **for educational and research purposes only**.  
Please ensure proper attribution when using or building upon this work.  
