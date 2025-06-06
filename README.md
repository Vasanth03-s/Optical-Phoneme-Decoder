# 🧠 Optical Phoneme Decoder

A deep learning-based lip-reading system that converts video of lip movements into phonemes. Built using PyTorch, this project implements a CNN-RNN-CTC architecture inspired by [LipNet](https://arxiv.org/abs/1611.01599).

---

## 🎯 Features

- ✅ End-to-end lip-reading model: video → phonemes
- 📦 Custom preprocessing and data loading pipeline
- 🧠 CNN + GRU architecture with CTC loss
- 📈 Training pipeline with loss/accuracy tracking
- 🎥 Inference support for phoneme prediction from new videos

---

## 🗂️ Notebook Structure

| Section | Description |
|--------|-------------|
| **0. Install & Import** | Set up libraries and environment |
| **1. Build Data Loading Functions** | Load, process, and prepare video + label data |
| **2. Create Data Pipeline** | Batching and sequence alignment |
| **3. Design the Neural Network** | CNN + Bidirectional GRU + CTC |
| **4. Training** | Training loop and evaluation |
| **5. Prediction** | Run inference on new video |
| **Test** | Final evaluation and testing |

---

## 🛠 Installation

```bash
git clone https://github.com/yourusername/optical-phoneme-decoder.git
cd optical-phoneme-decoder
pip install -r requirements.txt
