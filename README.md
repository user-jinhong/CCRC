# CCRC: A Change-Aware Captioning and Reasoning Chain for Image Change Captioning and Segmentation

Official implementation of the paper:
**"CCRC: A Change-Aware Captioning and Reasoning Chain for Image Change Captioning and Segmentation"**

📄 [Paper Title]: CCRC  
✍️ Authors: Jinhong Hua, Xiaoping Wang*, Shuyin Huang, Guojin Zhong, Kaitai Liu, Kai Lu*  
🏫 Affiliations: Hunan University, Guangxi Minzu University, National University of Defense Technology  
📅 Conference: [ECAI 2025] (TBD)

---

## 💡 Introduction

This repository provides the official PyTorch implementation of the **CCRC** framework, a dual-chain reasoning model for the new task of **Image Change Captioning and Segmentation (ICCS)**.

> CCRC decouples semantic reasoning and spatial segmentation by introducing Chain-of-Change-Captioning (CCC) and Chain-of-Change-Segmenting (CCS), and enhances change modeling via visual fusion, in-context guidance, and a change-aware token refiner.

---

## 🔧 Setup

```bash
git clone https://github.com/user-jinhong/CCRC.git
cd CCRC
pip install -r requirements.txt
