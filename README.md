# Shallow Neural Network for MRI Scan Classification

This project implements a **shallow neural network** for classifying MRI scan data using **TensorFlow/Keras** and **scikit-learn**.  
It demonstrates the full machine learning workflow from data loading and preprocessing to model training, evaluation, and visualization.

---
## Abstract
This study explores the transformative impact of deep learning on knee injury detection, specifically focusing on anterior 
cruciate ligament (ACL) tear identification within MRI scans using a shallow 3D convolutional neural network (CNN) model. 
Leveraging the MRNet dataset encompassing 1370 knee MRI scans, our approach employs deep learning techniques for binary 
classification of ACL injuries. With a remarkable balanced accuracy of 88%, our shallow 3D CNN model effectively discerns the 
presence or absence of ACL tears. This research underscores the paradigm shift brought by deep learning in automated ACL tear 
detection, showcasing its capacity to revolutionize orthopedic imaging. By harnessing the power of intricate three-dimensional MRI 
data, this work exemplifies how deep learning methodologies have significantly enhanced and transformed knee injury assessment, 
promising improved clinical decision support systems in orthopedic diagnostics.

## Dataset
The dataset applied here is sourced from Stanford MRNet dataset,publicly available at https://stanfordmlgroup.github.io/competitions/mrnet.
It's important to note that the dataset has been provided by the Stanford ML group.

## 📌 Overview
The model is designed for medical image classification tasks, specifically working with MRI scan datasets.  
It includes functions for:
- Loading and preprocessing MRI images
- Defining a shallow 3D convolutional neural network
- Training with learning rate scheduling
- Evaluating with metrics such as accuracy, F1-score, precision, recall, and ROC-AUC
- Displaying confusion matrices and performance curves

---

## 🛠 Requirements

Install dependencies from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Main Libraries Used:
NumPy – Numerical computations

Pandas – Data handling

Matplotlib – Visualization

scikit-learn – Metrics, preprocessing, and model utilities

TensorFlow/Keras – Model building and training

##Project Structure
```bash
your-project/
│
├── shallow_NN_code.ipynb   # Main Jupyter Notebook
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
├── data/                   # (Optional) Dataset or download instructions
├── .gitignore              # Ignore unnecessary files
└── assets/                 # (Optional) Images/screenshots
```

🚀 Usage
1. Clone the repository
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Open the notebook
```bash
jupyter notebook shallow_NN_code.ipynb
```

4. Run the cells to train and evaluate the model.

## 📊 Results
The notebook includes:
1. Model training accuracy/loss plots
2. Confusion matrices
3. Precision-Recall and ROC curves


**Evaluation Metrics:**

**Balanced Accuracy : 0.88**

**Precision : 0.9**

**Recall : 0.85**

**F1 Score: 0.87**

**ROC AUC Score : 0.9**


<img width="618" height="450" alt="image" src="https://github.com/user-attachments/assets/8f14dd97-1468-4b2d-81cc-9636fd077e68" />



