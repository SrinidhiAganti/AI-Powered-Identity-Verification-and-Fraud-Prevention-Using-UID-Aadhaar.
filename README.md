
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
● nagendra048/aadhar-dataset (Kaggle) — field images for OCR and detection.
● nagendra048/pan-card-dataset (Kaggle) — PAN card images for multi-doc
support.
● varunkumargera/aadhar-images (Kaggle) — alternative Aadhaar images.
● sparsh2002/govtiddataset (Kaggle) — mixed govt ID images.

## How to Run
```bash
pip install -r requirements.txt
python src/api/app.py
