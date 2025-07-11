# DDoS Detection in IoT: Deep Learning vs Machine Learning Analysis

This repository summarizes and analyzes the research paper titled:

**"DDoS Attack Detection in IoT: A Comparative Resource and Performance Analysis of Deep Learning and Machine Learning Models"**

Published in IEEE Access, 2025.

## 📄 Summary

The paper compares deep learning (DL) and traditional machine learning (ML) approaches for detecting Distributed Denial of Service (DDoS) attacks in Internet of Things (IoT) environments, focusing on resource and performance analysis. 

### Key Highlights:
- **Dataset**: CICDDoS2019 (CSV and image formats)
- **ML Models**: Random Forest, SVM, Logistic Regression
- **DL Models**: CNN, MobileNetV3, EfficientNetB0, Xception
- **Metrics Evaluated**: Accuracy, Precision, Recall, AUC, Inference Time, CPU and Memory Usage

### Conclusions:
This study demonstrates how CNN architectures such as MobileNetV3 and EfficientNetB0 can be leveraged to construct
a lightweight IDS optimized for resource-constrained IoT
environments. The proposed approach shows strong potential
for real-world applications, particularly in scenarios where
computational efficiency is critical.
Through a comparative analysis of deep learning and
traditional machine learning models, the study concludes
that lightweight deep learning architectures, such as MobileNetV3 and EfficientNetB0, provide a superior balance
between accuracy and computational cost. However, despite
their resource optimizations, their inference times remain too
high for strict real-time applications. Thus, these models are
more suitable for high-accuracy scenarios where inference
latency is acceptable rather than for real-time detection systems.
While traditional machine learning models demonstrate
high efficiency with minimal resource consumption, they
exhibit lower accuracy compared to lightweight CNNs. However, their significantly faster inference times make them
better candidates for real-time IDS deployment. Conversely,
lightweight CNNs achieve superior DDoS detection with
minimal retraining requirements and optimized resource utilization, making them well-suited for non-real-time IoT applications.
The findings highlight the importance of selecting models based on the specific requirements of the deployment
environment, ensuring an optimal trade-off between accuracy, computational efficiency, and resource constraints. Future research should explore real-world implementations and
scalability considerations to enhance the effectiveness of
IDS solutions in mitigating evolving cyber threats in IoT
ecosystems.

## 🧠 Authors

- Amer Abualhassan, Irfan Rashid, Farid Binbesh, Muhammad Imam

## 📚 License

This summary is provided for academic and research purposes only. Refer to the original paper for official content.

## 📎 Reference

IEEE Access. DOI: [10.1109/ACCESS.2025.3583855](https://doi.org/10.1109/ACCESS.2025.3583855)

**Citation:**
> A. Abulhassan, I. Rashid, M. Imam and F. Binbeshr, "DDoS Attack Detection in IoT: A Comparative Resource and Performance Analysis of Deep Learning and Machine Learning Models," in IEEE Access, doi: 10.1109/ACCESS.2025.3583855.

**Keywords:**
Accuracy; Internet of Things; Machine learning; Security; Denial-of-service attack;  Computational modeling; Measurement; Feature extraction; Real-time systems; Lightweight IDS; Distributed Denial of Service (DDoS); Internet of Things (IoT)
