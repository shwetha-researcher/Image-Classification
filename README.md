# 📷 Real-Time Image Classification for Fit Choice World (FCW)
This repository houses the documentation and project summary for a high-accuracy, lightweight computer vision system engineered during my Machine Learning internship at **Win Research Centre (WRC)**. The core pipeline automates meal and exercise logging for the FCW fitness ecosystem by cleanly categorizing media assets into three explicit classes: **Food**, **Fitness**, and **Random/Miscellaneous**.

* **Academic Evaluation:** Formally graded at **100/100** by internal evaluation panels.

---

## 🔬 Core Architecture & Edge Deployment
* **Model Framework:** Leveraged a **MobileNetV2** backbone using transfer learning via TensorFlow/Keras for its efficiency on resource-constrained client environments.
* **Optimization Layer:** Converted models into optimized **TensorFlow Lite (TFLite)** binaries, dropping the runtime deployment footprint down to a compact **3.7 MB**.
* **Production Latency:** Engineered a highly responsive **Python-Flask web interface** optimized to maintain an edge inference speed threshold under **~30ms**.

---

## 📈 Engineering Breakthroughs & Validation Metrics
* **Data Hygiene & Overfitting Mitigation:** Resolved initial category biases via targeted data augmentation techniques (scaling, rotation, flips) and systematic mid-term dataset expansion.
* **High-Precision Yield:** Achieved a **97% overall classification accuracy rate** with exceptional macro/weighted F1-scores and zero class bias across target domains.

---

## 📁 Repository Structure
```text
├── documents/
│   └── Internship_report.pdf  # Comprehensive technical summary report
└── README.md
```

---

## 📄 Project Documentation & Visuals
The comprehensive technical overview—complete with accuracy/loss training curves, model architecture logs, confusion matrices, and the Flask web interface interface screenshots—is available below:

👉 **[View the Technical Project Summary PDF](./documents/Internship_report.pdf)**
