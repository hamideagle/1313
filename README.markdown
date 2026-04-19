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
* 🖥️ **Modern GUI:** Clean interface built with PyQt6, featuring Dark/Light mode and bilingual support (English/Persian).
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

---

<h2 id="فارسی">🇮🇷 فارسی</h2>

### 📖 مرور کلی
**NeuroLogic Py** یک ابزار شبیه‌سازی گرافیکی و تعاملی است که با استفاده از Python و PyQt6 توسعه یافته است. این پروژه اصول اولیه یادگیری عمیق و شبکه‌های عصبی را با اعمال آن‌ها بر روی مسائل کلاسیک منطق دیجیتال بررسی می‌کند. این پروژه شامل دو ماژول اصلی است:
۱. **پرسپترون با قانون دلتا:** شبیه‌سازی گیت‌های منطقی ۳-ورودی (توازن فرد) و ۴-ورودی (اکثریت) با استفاده از پرسپترون تک‌لایه.
۲. **شبکه هاپفیلد (Hopfield):** شبیه‌سازی فلیپ‌فلاپ SR ناهمگام (Asynchronous SR Latch) با استفاده از فضای انرژی هاپفیلد.

### ✨ ویژگی‌ها
* 🖥️ **رابط کاربری مدرن:** طراحی تمیز با استفاده از PyQt6، دارای حالت تاریک/روشن (Dark/Light) و پشتیبانی از دو زبان (انگلیسی/فارسی).
* 📉 **مصورسازی بی‌درنگ:** یکپارچه‌سازی با Matplotlib برای نمایش نمودار خطا (Loss) و چشم‌انداز انرژی (Energy Landscape).
* 🧮 **مدل‌های ریاضی پیاده‌سازی شده:**
  * به‌روزرسانی وزن‌ها در پرسپترون: $\Delta w = \alpha \cdot (t - y) \cdot x$
  * تابع انرژی هاپفیلد: $E = -\frac{1}{2} s^T W s - b^T s$
* ⚙️ **پردازش چندنخی (Multithreading):** جلوگیری از فریز شدن رابط کاربری در حین آموزش شبکه.

### 🚀 نصب و اجرا
bash
git clone https://github.com/yourusername/NeuroLogic-Py.git
cd NeuroLogic-Py
pip install numpy pyqt6 matplotlib
python main.py

---

<h2 id="中文">🇨🇳 中文 (Chinese)</h2>

### 📖 概述
**NeuroLogic Py** 是一个使用 Python 和 PyQt6 构建的交互式图形仿真工具。它通过将深度学习和神经网络的基础知识应用于经典的数字逻辑问题来进行探索。该项目主要包含两个模块：
1. **Delta 感知机 (Delta Perceptron):** 使用单层感知机模拟 3 输入（奇校验）和 4 输入（多数）逻辑门。
2. **Hopfield 网络:** 利用 Hopfield 能量景观图模拟异步 SR 锁存器 (SR Latch)。

### ✨ 功能特点
* 🖥️ **现代 GUI:** 使用 PyQt6 构建的简洁界面，支持深色/浅色模式切换和双语（英语/波斯语）界面。
* 📉 **实时可视化:** 集成了 Matplotlib 画布，用于显示损失曲线 (Loss Curve) 和能量景观图 (Energy Landscape)。
* 🧮 **数学模型:**
  * 感知机权重更新公式: $\Delta w = \alpha \cdot (t - y) \cdot x$
  * Hopfield 能量函数: $E = -\frac{1}{2} s^T W s - b^T s$
* ⚙️ **多线程:** 在网络训练期间保持 UI 的流畅和非阻塞。

### 🚀 安装与使用
bash
git clone https://github.com/yourusername/NeuroLogic-Py.git
cd NeuroLogic-Py
pip install numpy pyqt6 matplotlib
python main.py
