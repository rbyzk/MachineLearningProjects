# 🥔 Potato Leaf Disease Detection using Deep Learning

This project applies **Convolutional Neural Networks (CNNs)** and **Transfer Learning** to classify potato leaves as either **healthy** or affected by **late blight** disease — a serious fungal infection that threatens crop yield.

🧪 Powered by deep learning and built for real-world agricultural use cases, the model aims to provide fast and accurate leaf health diagnostics.

---

## 📌 Project Highlights

✅ Built and trained a custom CNN model from scratch  
🧠 Applied transfer learning using **VGG16**, **MobileNetV2**, and **EfficientNetB0**  
📊 Compared model performance using accuracy, recall, and confusion matrices  
⚖️ Tackled data imbalance with augmentation and careful evaluation  
🧬 Focused on improving recall for the minority class (Late Blight)  
📁 Dataset: [Potato Health Dataset](https://www.kaggle.com/datasets/raju9822/potato-leaf-dataset)

---

## 📂 Dataset Overview

- **Classes**: `Healthy`, `Late Blight`  
- **Total Samples**: 430+ images  
  - 363 healthy  
  - 67 diseased  
- **Format**: JPG images categorized in folders  
- **Source**: Publicly available agricultural image dataset

---

## 🧠 Models Used

- 🔨 **Custom CNN**: Simple architecture with BatchNorm and Dropout  
- 🔁 **Transfer Learning**:
  - VGG16
  - MobileNetV2
  - EfficientNetB0

Each model was trained using ImageDataGenerator and evaluated on a held-out validation set.

---

## 📈 Evaluation Metrics

- Accuracy  
- Confusion Matrix  
- **Recall for Late Blight** (prioritized due to class imbalance)  
- Training time and inference speed  

---

## 🔬 Key Findings

- Custom CNN performed well but overfitting was observed  
- VGG16 and EfficientNetB0 achieved **100% recall** on late blight class  
- MobileNetV2 was fastest but slightly lower in accuracy  
- Dataset augmentation improved model generalization  
- Model comparison helped identify the most robust choice for deployment

---

## 🚀 Future Work

- Collect more diseased samples for class balance  
- Deploy the best-performing model as a **mobile app** or **web dashboard**  
- Add early blight as a third class for multi-class classification  
- Experiment with Grad-CAM for visual explanations

---

## 👩‍💻 Author

**Beyza Küçük**  
*Data Scientist & Data Analyst*  
📍 [Kaggle Profile](https://www.kaggle.com/beyzakucuk)

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and share with attribution.

---

> 🌱 Deep learning meets agriculture — protecting crops, one leaf at a time!
