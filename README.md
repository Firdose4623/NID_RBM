# 🧠 AI Meets Cybersecurity: Restricted Boltzmann Machines for Network Intrusion Detection

This repository contains the research paper:  
📄 **“A Systematic Approach for the Application of Restricted Boltzmann Machines in Network Intrusion Detection”**  
by *Arnaldo Gouveia Miguel Correia*, INESC-ID, Instituto Superior Técnico, Universidade de Lisboa.

---

## 📘 Overview

This paper explores how **Restricted Boltzmann Machines (RBMs)** — energy-based probabilistic models inspired by statistical physics — can learn hidden patterns in network data and distinguish **normal** from **malicious** traffic.

It introduces a **systematic training framework** for RBMs that includes:

- Weight initialization and pre-training with **Rectified Linear Units (ReLU)**
- Fine-tuning with **Sigmoid Units**
- Parameter optimization (**learning rate**, **momentum**, **weight decay**, etc.)
- Evaluation using the **UNB ISCX Intrusion Detection Dataset**

---

## 🧩 Key Takeaways

- RBMs can effectively detect network intrusions in an **unsupervised** manner  
- The approach bridges **machine learning** and **statistical physics**  
- Achieves stable classification accuracy with cross-validation and bootstrap methods  
- Demonstrates how simple energy-based models can still be powerful for cybersecurity  

---

## 📊 Dataset Used

**UNB ISCX Intrusion Detection Evaluation Dataset**

- Contains both normal and attack traffic  
- Attacks include DoS, R2L, U2R, and Probing  
- Each record represents a network flow with 40+ features  
- Balanced class distribution between normal and malicious data  

---

## Coming Soon

- Python implementation of RBM-based Intrusion Detection  
- Data preprocessing and visualization scripts  
- Experimental results reproduction using modern frameworks

  ---
