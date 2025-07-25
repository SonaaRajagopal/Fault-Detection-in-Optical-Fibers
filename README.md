# 🧠 Fault Detection in Optical Fibers using Deep Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Used-orange?logo=tensorflow)
![OpenCV](https://img.shields.io/badge/OpenCV-Used-informational?logo=opencv)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Used-yellow?logo=scikitlearn)
![License](https://img.shields.io/github/license/yourusername/Fault-Detection-in-Optical-Fibers)



## 📌 Overview

This repository contains a **deep learning-based system** for automated fault detection, diagnosis, and localization in **optical fiber communication networks**, using OTDR trace data and anomaly detection models such as **Variational Autoencoders (VAE)** and **Vision Transformers (ViTs)**.



## 🧪 Motivation

Optical fiber networks are critical for high-speed internet infrastructure. Detecting faults like:
- 🔴 Fiber cuts  
- ⚠️ Dirty connectors  
- 🔒 Fiber tapping (eavesdropping)  
- 🔧 Bad splices  

...is essential for maintaining **network reliability** and **minimizing downtime**.



## 📂 Dataset

- **Source**: Synthetic + Real OTDR trace data
- **Features**:  
  - Signal-to-Noise Ratio (SNR)  
  - Points P1–P30 (signal reflections)  
  - Class (fault type)  
  - Position  
  - Reflectance  
  - Loss  

📊 Size: `125,832` records  
📁 Format: `.csv` and `.png` trace visualizations



## 🧠 Model Architecture

- 🔹 **Preprocessing**: Normalization, Noise filtering  
- 🔹 **Model 1**: Variational Autoencoder (VAE) for anomaly detection  
- 🔹 **Model 2**: Vision Transformer (ViT) for trace image classification  
- 🔹 **Fusion**: Combined decision score from VAE + ViT for improved accuracy



## 🔧 Tools & Libraries

| Category             | Tools Used                                        |
|-|--|
| Programming          | Python, NumPy, Pandas                            |
| ML/DL Frameworks     | TensorFlow, Scikit-learn, OpenCV, Keras          |
| Visualization        | Matplotlib, Seaborn                              |
| ML Ops (optional)    | MLflow, Jupyter Notebooks                        |



## 📊 Results

- ✅ Accuracy (VAE): 94.2%  
- ✅ Accuracy (ViT): 96.8%  
- 🔁 Combined Accuracy: **98.3%**  
- ⚡ Fault localization precision: **< 3m margin of error**



## 🧠 Future Work

- 🔧 Integrate into SDN-based network controllers  
- 🛰️ Real-time monitoring using edge devices  
- 🧠 Train on real-world telco data  
- 📦 Package as an AI-powered diagnostic tool  



## 🤝 Contributions

Pull requests, feedback, and ideas are welcome!  
Don't forget to ⭐️ the repository if you find it useful.



## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


   
