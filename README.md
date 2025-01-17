# QuantumShield
# QuantumShield: A Readiness Analyzer for Post-Quantum Cryptography

![image](https://github.com/user-attachments/assets/8abe3e13-6f1f-428e-9787-4321191c9ff6)

## Overview

**QuantumShield** is a tool designed to analyze the cryptographic readiness of systems in anticipation of quantum computing threats. With the advent of quantum computers, traditional cryptographic algorithms like RSA, AES, and SHA could become vulnerable to attacks like Shor's and Grover's algorithms. This tool scans source code for these vulnerabilities and provides remediation suggestions for transitioning to post-quantum safe cryptographic methods.

## Features

- **Cryptographic Vulnerability Detection**: Scans the source code to identify traditional cryptographic algorithms (e.g., RSA, AES, SHA) that may be vulnerable to quantum attacks.
- **Quantum Vulnerability Analysis**: Maps each cryptographic algorithm to known quantum attacks and provides a risk assessment.
- **Remediation Recommendations**: Suggests post-quantum cryptographic alternatives such as lattice-based algorithms, hash-based signatures, and more.
- **Detailed Reporting**: Generates detailed reports, including CWE (Common Weakness Enumeration) references, descriptions, and suggestions for secure replacements.

## Supported Cryptographic Algorithms

- **RSA** (vulnerable to Shor's algorithm)
- **AES** (vulnerable to Grover's algorithm)
- **SHA** (vulnerable to collision finding attacks with quantum computing)

## Installation

### Prerequisites

Ensure you have Python 3.6+ installed on your machine. You'll also need `pip` to install Python packages.

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/QuantumShield.git
   cd QuantumShield
   
pip install -r requirements.txt

python quantumshield.py /path/to/your/file.py

![image](https://github.com/user-attachments/assets/9f6dbb2a-2d14-4251-9359-775477830617)


