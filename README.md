# Analysis of Deep and Graph Neural Networks for Enhanced DDoS Attack Detection

[![Published in IEEE](https://img.shields.io/badge/IEEE-Xplore-blue?style=for-the-badge&logo=ieee)](https://ieeexplore.ieee.org/abstract/document/11361499)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](./LICENSE)

## 📄 Publication
This repository contains the source code and experimental data for the research paper:
**"Analysis of Deep and Graph Neural Networks for Enhanced DDoS Attack Detection: A Pathway to Hybrid Models"**

**[Read the full paper on IEEE Xplore »](https://ieeexplore.ieee.org/abstract/document/11361499)**

---

## 🔍 Project Overview
This project evaluates and compares the effectiveness of **Deep Neural Networks (DNN)** and **Graph Neural Networks (GNN)** for detecting Distributed Denial of Service (DDoS) attacks.

While DNNs are traditionally used for feature-based detection, this research highlights the superior capability of GNNs in capturing the topological structure of network flows. The study proposes a pathway toward hybrid models that leverage the speed of DNNs and the structural awareness of GNNs.

## 📊 Key Findings

### 1. Deep Neural Networks (DNN)
* **Strengths:** Exceptional at handling high-volume, signature-based attacks.
* **Performance:** Achieved **99.34% accuracy** for TCP flood attacks.
* **Use Case:** Ideal for real-time detection of known, high-rate distinct threats.

### 2. Graph Neural Networks (GNN)
* **Strengths:** Superior at detecting **low-volume (stealth)** attacks and capturing relationships between network flows.
* **Performance:** Significantly outperformed DNNs in identifying subtle attack patterns (**97.56%** vs **91.23%**).
* **Use Case:** Best for detecting complex, distributed, and evolving threats where network topology matters.

### 📈 Performance Comparison Table
| Attack Type | DNN Accuracy | GNN Accuracy |
| :--- | :--- | :--- |
| **TCP Floods** | **99.34%** | 98.76% |
| **UDP Floods** | **98.87%** | 98.45% |
| **HTTP Floods** | **98.56%** | 97.89% |
| **Low-Volume (Stealth)** | 91.23% | **97.56%** |

## 🛠️ Technology Stack
* **Language:** Python 3.8+
* **Deep Learning:** PyTorch
* **Graph Learning:** PyTorch Geometric
* **Data Processing:** NumPy, Pandas, Scikit-learn
* **Visualization:** Matplotlib, Seaborn

## 🚀 Key Features
* **Hybrid Analysis:** A comparative study establishing the groundwork for combining DNN and GNN architectures.
* **Topology Awareness:** Utilizes graph-based learning to detect attacks based on node interactions rather than just isolated flow features.
* **Stealth Detection:** Specialized capability to identify "Low-Rate DDoS" attacks that often bypass traditional filters.

---

## ❝ Citation
If you use this code or our results in your research, please cite our paper:

```bibtex
@article{Athif2025DDoS,
  title={Analysis of Deep and Graph Neural Networks for Enhanced DDoS Attack Detection: A Pathway to Hybrid Models},
  author={Athif, Shayan and Sharukesh, M and Nidish, S R and Vignesh, V S and Sabapathy, Sundaresan and Sasi, Deepika and Jayakody, Dushantha Nalin K.},
  journal={IEEE Access}, 
  year={2025},
  publisher={IEEE},
  url={[https://ieeexplore.ieee.org/abstract/document/11361499](https://ieeexplore.ieee.org/abstract/document/11361499)}
}
