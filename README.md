# U-Net Image Segmentation Pipeline with PyTorch & Albumentations

This repository features a PyTorch implementation of the U-Net architecture for image segmentation, using the powerful `segmentation-models-pytorch` library. It includes Albumentations-based preprocessing, full training/validation loops, and prediction visualizations. The pipeline is easily adaptable to various domains, including biomedical imaging and aerial drone imagery.
![Screenshot from 2025-05-07 10-42-54](https://github.com/user-attachments/assets/ad8d4dc0-9539-49eb-8322-2ba5070ec24a)

![Screenshot from 2025-05-07 10-43-14](https://github.com/user-attachments/assets/d63ad9a5-9dff-4823-84e0-af23f4ab6b40)

---

## 🧠 Model Overview

- **Model Architecture**: U-Net
- **Backbone**: Pretrained encoders from `segmentation-models-pytorch`
- **Framework**: PyTorch
- **Data Augmentation**: Albumentations
- **Purpose**: Pixel-level segmentation of input images (e.g., semantic segmentation)

---

## 📂 Dataset

- **Dataset Name**: Semantic Drone Dataset  
- **Source & Citation**:  
  [http://dronedataset.icg.tugraz.at](http://dronedataset.icg.tugraz.at)  
  *License: Free for non-commercial academic use with proper citation. Redistribution is prohibited.*

---

## 📁 Project Structure

u-net-segmentation/
│
├── u-net.ipynb # Main notebook with full pipeline
├── requirements.txt # All dependencies for setup
├── README.md # Project overview (this file)
├── dataset/
│ ├── images/ # Input drone images
│ └── masks/ # Ground truth masks
├── outputs/
│ ├── model.pth # Trained model weights
│ └── predictions/ # Example output masks
└── utils/
└── dataset.py # Custom dataset class (if separated)

# U-Net Image Segmentation with PyTorch

This repository contains a PyTorch implementation of the U-Net architecture for image segmentation. Built with `segmentation-models-pytorch`, it supports customizable datasets and includes data preprocessing with Albumentations, training/validation loops, and prediction visualizations.

### 📂 Dataset
**Semantic Drone Dataset**  
🔗 [Dataset Link](https://www.tugraz.at/index.php?id=22387)  
📌 Citation: [http://dronedataset.icg.tugraz.at](http://dronedataset.icg.tugraz.at)

**License:**  
The dataset is free for non-commercial academic use. Redistribution is prohibited. Refer to the dataset page for full license terms.

---

### 🛠️ Technologies Used
- Python  
- PyTorch  
- segmentation-models-pytorch  
- Albumentations  
- OpenCV  
- NumPy, Matplotlib, Pandas  
- tqdm  

---


### 📃 License & Usage
This codebase is shared under the **MIT License** (see `LICENSE` file).

**Dataset:**  
Free for academic and non-commercial use. Redistribution of the dataset is not allowed.
