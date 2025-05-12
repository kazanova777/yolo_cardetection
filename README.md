# 🚗 European License Plate Recognition with YOLOv12 + TrOCR

This project combines **YOLOv12** for license plate detection and **TrOCR (Transformer OCR)** for recognizing the full license plate text, trained on the [European License Plates Dataset](https://www.kaggle.com/datasets/abdelhamidzakaria/european-license-plates-dataset).

---

## 📌 What we built

- ✅ **YOLOv12**: Detects license plates in full car images (can be reused or skipped if plates are already cropped)
- ✅ Works on real images and videos
- ✅ Training pipeline included — from dataset parsing to model training


<img width="646" alt="image" src="https://github.com/user-attachments/assets/06be660f-8a66-4cb0-a9bd-e4e12a7f4b38" />

---

## 📁 Dataset

I used:
**🔗 [European License Plates Dataset](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection/data)**

- Contains cropped license plate images
- File name **is the ground truth text**, e.g.:
