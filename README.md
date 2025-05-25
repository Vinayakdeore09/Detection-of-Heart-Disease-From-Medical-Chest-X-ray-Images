# 🫀 Detection of Heart Disease From Medical Chest X-ray Images

This repository contains a machine learning project that uses a convolutional neural network (DenseNet121) to detect **14 different heart-related conditions** from medical chest X-ray images.

## 📂 Dataset

The dataset contains chest X-ray images labeled for 14 diseases, sourced from:

🔗 [Google Drive Dataset](https://drive.google.com/drive/folders/1XC3iiz77TiEn8LgrQWCFQltThuaa9sb8?usp=sharing)

---

## 🧠 Model Used

We use a **pretrained DenseNet121** architecture fine-tuned on our dataset. This model is known for its efficiency and accuracy in image-based classification tasks.

### 🔍 Detected Heart Diseases:

1. Atelectasis
2. Cardiomegaly
3. Consolidation
4. Edema
5. Effusion
6. Emphysema
7. Fibrosis
8. Hernia
9. Infiltration
10. Mass
11. Nodule
12. Pleural Thickening
13. Pneumonia
14. Pneumothorax

---

## 📌 Features

* ✅ Multi-label classification using sigmoid outputs.
* ✅ Data augmentation and normalization with torchvision transforms.
* ✅ Transfer learning via DenseNet121.
* ✅ Evaluation using ROC-AUC and accuracy metrics.
* ✅ Visualization of predictions and performance.

---

## 📁 Project Structure

├── X-Ray.ipynb # Jupyter notebook with complete workflow

├── README.md # Project documentation

├── models/ # Trained model checkpoints (optional)

├── dataset/ # X-ray images and labels (linked via Drive)

└── utils.py # Helper functions (if any)


\---

🚀 How to Run

### 1. Clone the repository

bash

git clone [https://github.com/your-username/Detection-of-Heart-Disease-From-Medical-Chest-X-ray-Images.git](https://github.com/your-username/Detection-of-Heart-Disease-From-Medical-Chest-X-ray-Images.git)

cd Detection-of-Heart-Disease-From-Medical-Chest-X-ray-Images

### 2. Install dependencies

pip install -r requirements.txt

### 3. Open and run the notebook

jupyter notebook X-Ray.ipynb

#### ⚠️ Make sure to download and mount the dataset from the Google Drive link before running the notebook.

### 📊 Results

Validation Accuracy: \~XX%

ROC-AUC: XX (per class ROC can be visualized in the notebook)

Loss Function: Binary Cross Entropy

Optimizer: Adam

### 📸 Sample Predictions

Input X-ray	Ground Truth Labels	Predicted Labels

Cardiomegaly, Edema	Cardiomegaly, Edema

Effusion	Effusion

Visual examples and misclassification analysis are included in the notebook.

### 📚 Libraries Used

## 🙋‍♂️ Author

Vinayak Deore
