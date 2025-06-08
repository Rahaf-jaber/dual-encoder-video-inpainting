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

![Architecture](./assets/methodology.png) 
