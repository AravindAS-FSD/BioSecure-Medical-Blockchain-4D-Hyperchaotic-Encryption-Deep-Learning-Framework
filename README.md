# BioSecure-Medical-Blockchain

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)
![Ethereum](https://img.shields.io/badge/Blockchain-Ethereum-gray.svg)

## 📌 Overview
This repository contains the implementation of a multi-layered security framework for medical CT scans. Unlike traditional 2D chaotic systems, this project utilizes a **4D hyperchaotic map** seeded by **biometric DenseNet features** to ensure a massive key space ($2^{512}$).

## 🚀 Key Features
- **Biometric Authentication:** Face & Iris feature extraction using DenseNet-121.
- **ROI-Aware Segmentation:** U-Net model to isolate clinical lesions, ensuring data is only hidden in non-critical regions.
- **4D Hyperchaotic Encryption:** High-entropy confusion and diffusion resistant to differential attacks.
- **Decentralized Integrity:** IPFS-Go for off-chain storage and Ethereum (Ganache) for immutable audit trails.

## 🛠️ Tech Stack
- **Deep Learning:** PyTorch, Torchvision
- **Security:** OpenCV, NumPy (SVD), 4D chaotic oscillators
- **Blockchain:** Solidity, Ganache, Web3.py, IPFS-Go
- **Backend:** Flask API

## 📊 Performance
- **Biometric AUC:** 0.9899
- **Encryption NPCR:** > 99.6%
- **Visual Quality:** PSNR > 40dB (Lossless reconstruction)

## 📖 Usage
1. **Initialize Blockchain:** Start Ganache on `127.0.0.1:7545`.
2. **Start IPFS:** Run `ipfs daemon`.
3. **Run API:** `python app.py`
