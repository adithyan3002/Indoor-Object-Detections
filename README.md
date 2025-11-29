# 🏠 Indoor Object Detections  
A YOLO-based deep learning project capable of detecting almost all common indoor objects such as furniture, electronics, household items, and more.

This notebook was developed entirely in **Google Colab** and contains a full workflow including dataset loading, preprocessing, training, evaluation, and inference.

---

## 🚀 Features
- Detects a wide range of indoor objects  
- Trained using YOLO (Ultralytics)  
- Easy-to-run in Google Colab  
- Supports image, video, and realtime webcam inference  
- Model weights included (optional, if uploaded)  
- Clean and beginner-friendly Jupyter Notebook

---

📁 Dataset

This project uses an indoor object dataset containing various items typically found in homes, offices, and rooms.

You can use any YOLO-compatible dataset, or download one from Kaggle.

---

🔑 Kaggle API Setup (Required for Kaggle Dataset Users)

This project does not include a kaggle.json file for security reasons.
If you want to load Kaggle datasets inside the notebook:

📌 Step 1 — Download your Kaggle JSON

  1.  Visit: https://www.kaggle.com
    
  2.  Click your profile → Settings
    
  3.  Scroll to API
    
  4.  Click Create New API Token
    
  5.  A file named kaggle.json will download

📌 Step 2 — Upload it to Colab

  Inside the notebook, run:
  
  from google.colab import files
  files.upload()   # Upload kaggle.json here


Then:

  !mkdir -p ~/.kaggle
  
  !cp kaggle.json ~/.kaggle/
  
  !chmod 600 ~/.kaggle/kaggle.json

---

⭐ If you like this project

Consider giving the repo a star on GitHub!

---
