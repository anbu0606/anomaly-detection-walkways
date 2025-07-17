# anomaly-detection-walkways
Anomaly detection pipeline using Faster R-CNN for pedestrian walkways.
# 🚶 Region-Based Scalable Smart System for Anomaly Detection in Pedestrian Walkways

This project implements an anomaly detection pipeline using Region-based Scalable Convolutional Neural Networks (RS-CNN) to identify threats and unusual activities in pedestrian walkways. Built using Detectron2 and PyTorch, the system leverages Faster R-CNN and Region Proposal Networks (RPN) for high-accuracy detection.

## 📌 Objective

To detect anomalies in pedestrian walkways automatically using deep learning-based computer vision, thereby enhancing surveillance efficiency and reducing human monitoring efforts.

---

## 🧠 Key Features

- ⚙️ **Faster R-CNN & RPN:** Region-based object detection pipeline.
- 🎯 **97% Detection Accuracy:** Achieved on UCSD Anomaly Dataset.
- 📈 **COCO Evaluation Metrics:** Used for model performance validation.
- 🧰 **Custom Trainer:** Developed to enable flexible training and validation.
- 🚀 **Google Colab Integration:** Utilizes GPU acceleration for training.
- 📦 **Anchor Box Tuning:** Supports scalability for objects of varying sizes.

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Detectron2
- Google Colab
- OpenCV
- COCO Evaluation Tools

---

## 📂 Dataset

**UCSD Anomaly Detection Dataset**  
- **Peds1:** 34 training + 36 testing videos  
- **Peds2:** 16 training + 12 testing videos  
- 📥 [Dataset Link](http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm)

---

## 🔁 Workflow

1. **Preprocessing:** Video sequences are split into frames.
2. **Data Annotation:** Labeled images using COCO format for training.
3. **Model Training:** RS-CNN model trained on Colab using Detectron2.
4. **Evaluation:** Assessed using COCO metrics and test dataset.
5. **Visualization:** Anomalies overlaid on images using Detectron2 visualizer.

---

## 🚧 Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/region-based-anomaly-detection.git
   cd region-based-anomaly-detection
