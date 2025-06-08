# Dual-Encoder Video Inpainting
**Rahaf Jaber, Saeed Anwar, Muhammad Usman, Omar Hammad**
## ✨ Overview

This repository provides the official PyTorch implementation of our paper:

📄 **Video Inpainting with Dual-Encoder Enhancement: Striking the Balance Between Accuracy and Efficiency**  
We introduce a **dual-encoder video inpainting model** that integrates both lightweight CNN and ResNet-50 encoders to enhance spatial detail and semantic context. The model builds upon ProPainter and outperforms previous state-of-the-art approaches such as E2FGVI in quality–efficiency trade-offs.

---

## 🧠 Methodology

The architecture comprises:
- **Recurrent Flow Completion (RFC)**  
- **Dual-Domain Propagation (DDP)**  
- **Dual-Encoder Feature Extraction** (CNN + ResNet-50)  
- **Mask-Guided Sparse Video Transformer (MSVT)**

![Architecture](./methodology.jpg) 

## 🏆 Results

**Performance on DAVIS Dataset:**

| Model               | PSNR ↑ | SSIM ↑  | VFID ↓ | Runtime ↓ |
|--------------------|--------|---------|--------|-----------|
| ProPainter         | 33.02  | 0.9627  | 0.115  | 0.057 s   |
| E2FGVI             | 33.01  | 0.9721  | 0.116  | 0.085 s   |
| Ours (ResNet-50)   | **33.77** | 0.9660  | **0.115**  | **0.049 s** |
| Ours (Efficient)   | 32.96  | 0.9622  | 0.117  | **0.042 s** |

---
