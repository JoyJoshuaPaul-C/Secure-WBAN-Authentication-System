# Secure WBAN Authentication System  

## 📌 Overview  
This project introduces a **Four-Factor Mutual Authentication Protocol** designed for secure communication in **Wireless Body Area Networks (WBANs)**. It leverages face recognition, cryptographic operations, and lightweight computation techniques to ensure robust security in healthcare sensor networks.  

## 🚀 Features  
- **Four-Factor Authentication:** Combines device, user credentials, biometrics (face recognition), and session-specific parameters for enhanced security.  
- **Efficient Security Operations:** Optimized with XOR operations and reduced cryptographic overhead using SHA-256.  
- **Robust Against Attacks:** Validated for resilience against various security threats like replay, impersonation, and man-in-the-middle attacks.  
- **Simulation Testing:** Verified using BAN Logic and AVISPA for protocol correctness and security assurance.  

## 🛠️ Technologies Used  
- **Programming Language:** Python  
- **Libraries:** OpenCV, NumPy, PyCryptodome  
- **Simulation Tools:** BAN Logic, AVISPA  
- **Tools:** Jupyter Notebook  

## 📂 Project Structure  
```
Secure-WBAN-Authentication/  
│
├── src/                   # Source code  
│   ├── authentication.py  # Authentication protocol implementation  
│   ├── face_recognition.py# Face recognition module  
│   ├── hash_operations.py # Cryptographic operations  
│   └── utils.py           # Utility functions  
├── tests/                 # Test cases for authentication protocol  
├── docs/                  # Documentation  
├── data/                  # Sample data for testing  
├── results/               # Simulation and validation results  
├── requirements.txt       # Dependencies  
└── README.md              # Project documentation  
```  

## ⚙️ Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/Secure-WBAN-Authentication.git  
   cd Secure-WBAN-Authentication  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

## 📊 How It Works  
1. **Face Recognition:**  
   - Captures and verifies user identity via facial features.  
   - Utilizes OpenCV for real-time face detection.  
2. **Cryptographic Operations:**  
   - Implements secure key exchanges and data hashing using SHA-256.  
   - Reduces computation with lightweight XOR operations.  
3. **Validation:**  
   - Ensures protocol correctness with BAN Logic analysis.  
   - Simulates security scenarios using AVISPA.  

## 🧪 Usage  
1. Run the face recognition module:  
   ```bash  
   python src/face_recognition.py  
   ```  
2. Execute the authentication protocol:  
   ```bash  
   python src/authentication.py  
   ```  
3. Review results in the `results/` folder.  

## 📖 Results  
- **Security Validations:** Passed tests for resistance to replay, impersonation, and man-in-the-middle attacks.  
- **Efficiency:** Achieved reduced computational load suitable for WBAN environments.  

## 🌟 Future Enhancements  
- Integrate multi-modal biometric verification (e.g., fingerprint, voice).  
- Extend support for IoT healthcare devices.  
- Incorporate real-time monitoring and alert systems.  

## 🤝 Contribution  
We welcome contributions to enhance this project. Fork the repository, make your changes, and submit a pull request!  

 

