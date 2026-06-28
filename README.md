

  # 🍎 Apple Disease Detection Using CNN



This project utilizes a **Convolutional Neural Network (CNN)** to detect and classify various diseases in apple leaves. By leveraging deep learning, the model provides an automated way to identify plant health, which is essential for precision agriculture.

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Workflow](#-project-workflow)
- [Project Structure](#-project-structure)
- [Performance](#-performance)
- [Conclusion](#-conclusion)

---

## 📝 Overview
The primary goal of this project is to assist in early disease detection for apple orchards. The model processes leaf images to distinguish between healthy leaves and various disease patterns, helping reduce manual inspection time and effort.

---

## 🚀 Key Features
* **Data Preprocessing:** Automated resizing, normalization, and path separation.
* **Data Augmentation:** Techniques applied to improve model generalization.
* **Analysis:** Includes class distribution analysis and empty folder detection.
* **Visualization:** Training/Validation loss-accuracy graphs, confusion matrices, and prediction results.
* **Robustness:** Detailed analysis of overfitting and underfitting.

---

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Language** | Python |
| **Deep Learning** | TensorFlow / Keras |
| **Libraries** | NumPy, Pandas, Matplotlib, OpenCV, Scikit-learn |
| **Environment** | Google Colab |

---

## 🏗️ Project Workflow
1. **Load Dataset:** Importing and organizing the image dataset.
2. **Preprocessing:** Data cleaning and image resizing.
3. **Augmentation:** Generating variations of training images to boost accuracy.
4. **CNN Architecture:** Designing and training a custom Sequential model.
5. **Evaluation:** Analyzing performance metrics and visualizing outcomes.

---

## 🏗️ Model Workflow
1. **Data Loading:** Importing and analyzing the dataset.
2. **Preprocessing:** Normalization and image augmentation.
3. **Model Building:** Designing a sequential CNN architecture (Conv2D, MaxPooling, Dropout layers).
4. **Training:** Compiling with Adam optimizer and categorical cross-entropy loss.
5. **Evaluation:** Testing performance on the validation set.

---


## 📊 Results
The model demonstrates high accuracy in distinguishing between various apple disease classes and healthy leaves, effectively proving the potential for automated agricultural diagnostics.

---
## Output

<img width="1536" height="1024" alt="output" src="https://github.com/user-attachments/assets/90bd0f47-c2c7-4748-9f02-4a12c85ec551" />

---
## Project Workflow
<img width="1024" height="559" alt="Apple Disease workflow" src="https://github.com/user-attachments/assets/f3fd0e7f-4319-4ddd-96a3-ffdfb23052fc" />

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone [repository-link]


## 📂 Project Structure
```text
├── dataset/            # Folder containing leaf images
├── models/             # Saved model files (.h5 / .keras)
├── CNN_Project.ipynb   # Main Jupyter Notebook
└── README.md           # Documentation

---
# 👩‍💻 Author

**Minal Sadiq**
Data Science 

---

⭐ If you found this project useful, consider giving it a star.
