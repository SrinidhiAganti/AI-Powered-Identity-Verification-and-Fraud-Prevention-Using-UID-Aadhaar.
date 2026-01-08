# AI-Powered-Identity-Verification-and-Fraud-Prevention-Using-UID-Aadhaar.
This project leverages AI-OCR, deep learning, and computer vision to automate KYC document verification, detect forged or tampered documents, and generate fraud-risk scores. Built with Python, Azure AI concepts, and a lightweight HTML/CSS/JavaScript frontend for demonstration and academic use.
# AI-Powered Identity Verification and Fraud Prevention Using UID Aadhaar

This project implements an AI-based identity verification and fraud detection system using Aadhaar and other KYC documents.

## Features
- AI-OCR based Aadhaar data extraction
- Aadhaar format validation
- Deep learning based fraud detection (tampering & mismatch)
- REST API for KYC workflow integration

## Tech Stack
- Python
- OpenCV
- Tesseract OCR
- PyTorch
- Flask
- Azure AI (conceptual integration)

## Dataset
Uses open-source and synthetic Aadhaar-style datasets (Kaggle).

## How to Run
```bash
pip install -r requirements.txt
python src/api/app.py
