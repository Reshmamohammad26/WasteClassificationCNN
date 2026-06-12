# Virtual Internship Project on Waste Classification Using CNN

## 📌 Project Overview

This project focuses on classifying waste into two categories:

* Organic Waste
* Recyclable Waste

A Convolutional Neural Network (CNN) model is used to automatically identify the waste category from images. The project was developed as part of a Virtual Internship program to demonstrate the application of Deep Learning and Computer Vision in waste management and environmental sustainability.

---

## 📂 Dataset

Dataset used for this project:

**Waste Classification Data**

https://www.kaggle.com/datasets/techsash/waste-classification-data

The dataset contains:

* Organic Waste (O)
* Recyclable Waste (R)

Directory Structure:

```text
dataset/
│
├── TRAIN/
│   ├── O/
│   └── R/
│
└── TEST/
    ├── O/
    └── R/
```

---

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* CNN (Convolutional Neural Network)

---

## 📦 Required Libraries

Install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn opencv-python pillow scikit-learn tensorflow tqdm
```

---

## 🚀 Steps to Run the Project

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd WasteClassificationCNN
```

### Step 2: Download the Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/techsash/waste-classification-data

Extract the dataset folder into the project directory.

### Step 3: Configure Dataset Paths

```python
train_path = "dataset/TRAIN"
test_path = "dataset/TEST"
```

### Step 4: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn opencv-python pillow scikit-learn tensorflow tqdm
```

### Step 5: Run the Notebook

Open Jupyter Notebook or VS Code and execute:

```bash
wasteclassification.ipynb
```

### Step 6: Train the CNN Model

The model architecture consists of:

* Conv2D Layer (32 Filters)
* MaxPooling2D
* Conv2D Layer (64 Filters)
* MaxPooling2D
* Conv2D Layer (128 Filters)
* MaxPooling2D
* Flatten Layer
* Dense Layers
* Dropout Layers
* Output Layer

### Step 7: Evaluate the Model

Training and validation accuracy/loss graphs are generated after training.

### Step 8: Test Custom Images

Load a custom image and use the prediction function to classify waste as:

* Organic Waste
* Recyclable Waste

---

## 🧠 CNN Architecture

```text
Input Image (224x224x3)
        │
Conv2D (32)
        │
MaxPooling2D
        │
Conv2D (64)
        │
MaxPooling2D
        │
Conv2D (128)
        │
MaxPooling2D
        │
Flatten
        │
Dense (256)
        │
Dropout (0.5)
        │
Dense (64)
        │
Dropout (0.5)
        │
Dense (2)
        │
Output
```

---

## 📊 Results

The model successfully classifies waste images into:

* Organic Waste
* Recyclable Waste

Achieved validation accuracy of approximately **89%** during training.

---

## 🌍 Applications

* Smart Waste Segregation
* Recycling Systems
* Environmental Monitoring
* Smart City Solutions
* Automated Waste Management

---

## 👩‍💻 Author

Mohammad Reshma

B.Tech Computer Science and Engineering (AI & ML)

Vaagdevi College of Engineering

Graduation Year: 2026

---

## 📜 License

This project is developed for educational and learning purposes as part of a Virtual Internship Project.
