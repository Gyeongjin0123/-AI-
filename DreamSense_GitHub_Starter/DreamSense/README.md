# DreamSense: Embedded AI for Microdream Capture and Visualization

**DreamSense** is the world’s first embedded AI system that detects and reconstructs microdreams in real-time during sleep using multimodal neural signals.

## 🧠 Features
- Realtime microdream detection using EEG/EMG/EOG
- TinyML-based AI model for ultra-low power inference
- Visual output of reconstructed dream summaries
- Fully wearable embedded system

## 🛠️ Hardware
- MCU: STM32F746 / ESP32-S3
- Sensors: EEG (OpenBCI), EMG, GSR
- Power: LiPo battery / USB

## 📦 Directory Overview
- `/hardware`: Schematics and BOM
- `/firmware`: Embedded C/C++ code + TFLite model
- `/ai_model`: Dream reconstruction model (Python)
- `/visualization`: GAN-generated dream reconstructions
- `/experiments`: Data logs and scripts

## 🚀 Getting Started
1. Clone the repo  
2. Flash `/firmware` to STM32 board  
3. Run `/ai_model/train_microdream_model.ipynb`  
4. Upload real-time results to `/visualization`

## 📄 License
MIT License
