<!-- Ảnh tổng quan, căn giữa, phóng to -->
<p align="center">
  <img src="overview.png" width="800"/>
</p>

<!-- Ảnh poster chính thức, căn giữa, phóng to -->
<p align="center">
  <img src="Official.png" width="800"/>
</p>


This repository contains the final project for the course CS117 – Introduction to Data Science, conducted at [Your University Name]. Our project is titled:
"A Real-Time Driver Alertness Detection System Using Facial Video and Heart Rate Signals."

The motivation behind this project stems from the increasing number of traffic accidents caused by drowsy or distracted driving. Traditional in-car alert systems often rely on limited inputs (such as eye-blink detection alone) or are not designed for real-time performance. Our system aims to address this gap by combining visual data from a frontal camera with physiological signals (heart rate) to make more accurate and timely predictions about a driver's alertness state.

We use a hybrid approach that leverages deep learning for facial expression analysis and machine learning for physiological signal classification. Specifically, a Vision Transformer (ViT) is used to process facial frames, while features derived from heart rate signals are processed by traditional classifiers such as XGBoost or Random Forest. The final system is capable of running in real-time, providing immediate output on whether the driver is alert or drowsy.

This solution could serve as a foundational component for future advanced driver-assistance systems (ADAS), contributing to safer roads and more intelligent in-vehicle systems.
Hỗ trợ đa người dùng trong xe (multi-face detection)

