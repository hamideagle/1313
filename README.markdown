<div align="center">

# 🧠 NeuroLogic Py ⚡

**A Powerful GUI-Based Simulator for Neural Networks, Logic Gates & SR Latches**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![PyQt6](https://img.shields.io/badge/PyQt-6.0+-green.svg?style=flat&logo=qt&logoColor=white)](https://riverbankcomputing.com/software/pyqt/)
[![NumPy](https://img.shields.io/badge/NumPy-Optimized-blue.svg?style=flat&logo=numpy&logoColor=white)](https://numpy.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[English](#english) | [فارسی](#فارسی) | [中文](#中文)

</div>

---

<h2 id="english">🇬🇧 English</h2>

### 📖 Overview
**NeuroLogic Py** is an interactive, graphical simulation tool built with Python and PyQt6. It explores the fundamentals of Deep Learning and Neural Networks by applying them to classic digital logic problems. The project consists of two main modules:
1. **Delta Perceptron:** Simulates 3-input (Odd Parity) and 4-input (Majority) logic gates using a single-layer perceptron.
2. **Hopfield Network:** Simulates an asynchronous SR Latch utilizing the Hopfield energy landscape.

### ✨ Features
* 🖥️ **Modern GUI:** Clean interface built with PyQt6, featuring Dark/Light mode and bilingual support.
* 📉 **Real-time Visualization:** Integrated Matplotlib canvas to display loss curves and energy landscapes.
* 🧮 **Mathematical Models:** 
  * Perceptron Weight Update: $\Delta w = \alpha \cdot (t - y) \cdot x$
  * Hopfield Energy Function: $E = -\frac{1}{2} s^T W s - b^T s$
* ⚙️ **Multithreading:** Non-blocking UI during network training.

### 🚀 Installation

```bash
git clone https://github.com/yourusername/NeuroLogic-Py.git
cd NeuroLogic-Py
pip install numpy pyqt6 matplotlib
python main.py
