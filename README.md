# Lightweight-Dual-Stage-Feature-Decoupling-Framework
# 🧠 Code Pre-release Statement  

**This repository contains the official implementation for the paper "Deep Covariance Denoising and Attention-Guided On-Grid Classification: A Dual-Stage Network for Robust Underwater DOA Estimation"**  

## 📜 Current Status  
- 🔒 Core code and experimental data are temporarily withheld to ensure data security and privacy  
- 📊 All experimental results in the paper were obtained using the complete implementation in this repository  
- ⚙️ Model architecture details are described in Section 2 (Proposed Method) of the paper  

## 🚀 Release Plan  
| Stage | Content | Timeline |
|-------|---------|----------|
| Paper Acceptance | Open-source basic framework code | Within 72 hours of acceptance |
| Formal Publication | Release complete training/inference code | Upon paper online publication |
| Supplementary Verification | Public benchmark dataset release | Within 30 days of publication |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔍 Future Contents  
```bash
├── core_architecture/                 # Core model implementation
│   ├── JCA-CNN.py                     # Joint Channel-Attention Convolutional Module
│   └── Encoer.py                      # Dual-stage feature decoupling framework-Encoder
│   └── Decoer.py                      # Dual-stage feature decoupling framework-Decoder
├── pretrained_models/                 # Pre-trained weights
│   ├── simulation_freq_model_M10.pth  # Simulated signal model
│   └── simulation_freq_model_M20.pth  # Simulated signal model
├── training_scripts/                  # Training scripts
│   ├── main_trian.py                  # Main script for simulated data training
│   └── load_cov_matrix.py             # Parameters for simulated data loading
└── test_scripts/                      # Testing scripts
│    └── main_test.py                  # Main script for simulated data testing
├─── ...                               # Related code scripts
