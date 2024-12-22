# Quantum-Cryptography-Vulnerabilities
A dataset of 1000 simulated cryptographic vulnerabilities, including weaknesses, quantum computing threats, and quantum-safe remediation actions. Designed for assessing cryptographic readiness, it supports research, testing, and the development of quantum-threat assessment tools.
# Quantum Cryptography Vulnerabilities Dataset

## Overview
This repository contains a dataset of 1000 entries cataloging simulated vulnerabilities in cryptographic algorithms. Each row includes:
- The cryptographic algorithm (e.g., RSA-2048, AES-128).
- The identified weakness in the algorithm.
- The quantum computing threat associated with the vulnerability (e.g., Shor's Algorithm, Grover's Algorithm).
- Recommended actions to transition to quantum-safe cryptography.

## Purpose
This dataset aims to:
1. Assist in evaluating cryptographic systems for quantum readiness.
2. Provide researchers and developers with a reference for understanding quantum threats.
3. Enable the development of quantum-threat assessment tools.

## Dataset Schema
- `Algorithm`: The name of the cryptographic algorithm.
- `Weakness`: A brief description of the vulnerability.
- `Quantum Threat`: The quantum-based attack that can exploit the vulnerability.
- `Action`: Suggested quantum-safe cryptographic alternatives or mitigation steps.

## Example
| Algorithm  | Weakness                | Quantum Threat        | Action                  |
|------------|-------------------------|-----------------------|-------------------------|
| RSA-2048   | Key size too small      | Shor’s Algorithm      | Replace with Kyber      |
| AES-128    | Moderate key length     | Grover’s Algorithm    | Upgrade to AES-256      |
| ECC-P256   | Vulnerable curve params | Shor’s Algorithm      | Use Dilithium           |

## How to Use
1. Clone the repository:
   ```bash
      git clone https://github.com/chakriceoq/Quantum-Cryptography-Vulnerabilities.git

The dataset contains 10 unique encryption algorithms. Here is the list of unique algorithms:

RSA-3072
AES-128
SHA-256
3DES
RSA-2048
DES
ECC-P256
Blowfish
AES-256
SHA-512
