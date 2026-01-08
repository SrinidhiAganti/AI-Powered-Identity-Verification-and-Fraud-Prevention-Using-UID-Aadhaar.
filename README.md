
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
