# DeepGuard: Audio Deepfake Watermarking System

DeepGuard is a system to embed imperceptible cryptographic watermarks into audio files and later verify their authenticity to combat audio deepfakes in journalism.

## Features
- *Watermark Embedding:* Uses frequency-domain transforms and RSA digital signatures.
- *Tamper Detection:* A machine learning module (simulated here) to detect any adversarial tampering.
- *File Management:* A secure file manager that prevents duplicate uploads.
- *User Interface:* A clean, interactive UI built with PyQt5 for selecting audio files, embedding watermarks, detecting tampering, and verifying with a simulated blockchain ledger.

## Directory Structure
DeepGuard/
├── app.py
├── README.md
├── requirements.txt
├── ui/
│  ├── init.py
│  └── main_window.py
├── watermark/
│  ├── init.py
│  ├── crypto.py
│  ├── detect.py
│  └── embed.py
├── utils/
│  ├── init.py
│  ├── audio_processing.py
│  └── file_manager.py
├── ml/
│  ├── init.py
│  └── tamper_detection.py
└── blockchain/
    ├── init.py
    └── ledger.py
