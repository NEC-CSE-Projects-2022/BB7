# 🌱 GrowSmart  
## A Dual-Stage Machine Learning and Deep Learning Framework for Urban Agriculture

GrowSmart is an intelligent agriculture assistance system designed to help farmers and urban gardeners make accurate, data-driven decisions. The system integrates Machine Learning models for crop and fertilizer recommendation with a Deep Learning–based plant disease detection module using ResNet9.

---

## 🚀 Features

- Crop Recommendation System  
- Fertilizer Recommendation System  
- Plant Disease Detection using ResNet9 CNN  
- Real-time Weather Data Integration  
- Web-based Interface using Flask  
- Pre-trained Machine Learning and Deep Learning models  

---

## 🧠 Technologies Used

### Backend
- Python  
- Flask  
- NumPy  
- Pandas  
- Scikit-learn  
- PyTorch  
- Torchvision  

### Frontend
- HTML  
- CSS  
- Bootstrap  

### Models
- XGBoost (Crop Recommendation)  
- Rule-based Logic (Fertilizer Recommendation)  
- ResNet9 (Plant Disease Detection)  

---

## 🧩 System Architecture


---

## 📊 Dataset (Plant Disease Detection)

- Dataset Name: PlantVillage  
- Total Images: ~54,000+  
- Number of Classes: 38  
- Image Type: RGB (.jpg)  
- Source: Kaggle  

🔗 Dataset Link:  
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

⚠️ **Note:** Do NOT upload dataset images to GitHub. Download the dataset locally and arrange it as shown below.

---

## 📁 Expected Dataset Structure


This structure is compatible with `torchvision.datasets.ImageFolder`.

---

## 🧪 Usage Example (PyTorch)

```python
from torchvision import transforms
from torchvision.datasets import ImageFolder
from torch.utils.data import DataLoader

transform = transforms.Compose([
    transforms.Resize((256, 256)),
    transforms.ToTensor(),
])

train_dataset = ImageFolder(
    "plant_disease_dataset/train",
    transform=transform
)

train_loader = DataLoader(
    train_dataset,
    batch_size=32,
    shuffle=True
)

