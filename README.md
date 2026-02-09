# Team Number – BB7

# 🌱 GrowSmart  
## A Dual-Stage Machine Learning and Deep Learning Framework for Urban Agriculture

---

## 👥 Team Info

- **22471A05B5 — Nayeem Patalam** ([LinkedIn](https://www.linkedin.com/in/patalam-nayeem-14669b360/))  
  _Work Done: Project lead, system design, ML model development, integration, documentation_

- **22471A0571 — Addaki Varun Yadav** ([LinkedIn](https://www.linkedin.com/in/kuppala-purna-chandra-rao-1b85a6282))  
  _Work Done: Dataset collection, preprocessing, exploratory data analysis (EDA), model training support_

- **22471A05A5 — Kuppala Purna Chandra Rao** ([LinkedIn](https://www.linkedin.com/in/addanki-varun-yadav))  
  _Work Done: Deep learning model implementation (ResNet9), testing, performance evaluation_

---

## 🧾 Abstract

Urban agriculture faces challenges such as improper crop selection, inefficient fertilizer usage, and delayed plant disease identification, which directly impact productivity and sustainability. This project, **GrowSmart**, presents a dual-stage intelligent agriculture assistance system that integrates Machine Learning and Deep Learning techniques to support informed decision-making. The system recommends suitable crops based on soil and climatic parameters, suggests appropriate fertilizers using rule-based logic, and detects plant diseases from leaf images using a ResNet9 convolutional neural network. By combining predictive analytics with image-based disease diagnosis in a unified web platform, GrowSmart aims to enhance agricultural efficiency, reduce resource wastage, and support smart farming practices in urban environments.

---

## 📄 Paper Reference (Inspiration)

👉 **[Smart Farming: Enhancing Urban Agriculture Through Predictive Analytics and Resource Optimization  
– IEEE Authors](https://ieeexplore.ieee.org/document/10843189)**  

This IEEE paper served as the conceptual inspiration for integrating machine learning–based recommendations with deep learning–based disease detection.

---

## 🚀 Our Improvement Over Existing Paper

- Implemented a **dual-stage framework** combining ML and DL in a single system  
- Used **ResNet9** for efficient and lightweight disease detection  
- Added **fertilizer recommendation** using rule-based logic  
- Developed a **complete Flask-based web application**  
- Improved usability by providing **end-to-end decision support** instead of isolated predictions  

---

## 🌱 About the Project

GrowSmart is an intelligent web-based agriculture support system designed for farmers and urban gardeners.

- The system predicts the **most suitable crop** based on soil nutrients and weather conditions  
- It suggests **fertilizer corrections** by comparing current and ideal NPK values  
- It detects **plant diseases** from uploaded leaf images and provides treatment suggestions  

**Workflow:**  
User Input → Data Preprocessing → ML/DL Models → Prediction Results → Web Interface Output

---

## 📊 Dataset Used

👉 **[PlantVillage Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)**  

**Dataset Details:**
- Total Images: ~54,000+  
- Number of Classes: 38  
- Image Type: RGB (.jpg)  
- Used for training and testing the ResNet9 disease detection model  

---

## ⚙️ Dependencies Used

- Python  
- Flask  
- NumPy  
- Pandas  
- Scikit-learn  
- XGBoost  
- PyTorch  
- Torchvision  
- HTML, CSS, Bootstrap  

---

## 🔍 EDA & Preprocessing

- Checked missing and inconsistent values in crop recommendation dataset  
- Normalized numerical features such as NPK, temperature, and rainfall  
- Image resizing and tensor conversion for deep learning  
- Dataset split into training, validation, and testing sets  

---

## 🧠 Model Training Info

- **Crop Recommendation:** XGBoost classifier trained on soil and climate parameters  
- **Fertilizer Recommendation:** Rule-based logic using ideal NPK ranges  
- **Disease Detection:** ResNet9 CNN trained on PlantVillage dataset  
- Optimized using appropriate loss functions and batch training  

---

## 🧪 Model Testing / Evaluation

- Accuracy and prediction consistency evaluated for crop recommendation  
- Rule-based validation for fertilizer suggestions  
- Disease detection evaluated using validation accuracy and prediction confidence  
- Model tested with unseen images for generalization performance  

---

## 📈 Results

- Accurate crop recommendations for varying soil and climate conditions  
- Effective fertilizer correction suggestions reducing nutrient imbalance  
- High accuracy in plant disease classification using ResNet9  
- Successful integration of all modules into a single web application  

---

## ⚠️ Limitations & Future Work

**Limitations:**
- Limited to predefined crop categories  
- Requires good image quality for disease detection  

**Future Work:**
- Upgrade ResNet9 to EfficientNet  
- Mobile application development  
- Multilingual support for farmers  
- IoT sensor integration for real-time data  
- Cloud deployment for scalability  

---

## 🌐 Deployment Info

- Backend deployed using Flask  
- Models loaded as pre-trained `.pkl` and `.pth` files  
- Web interface accessible via local server  
- Can be extended to cloud platforms like AWS or Azure  

---
