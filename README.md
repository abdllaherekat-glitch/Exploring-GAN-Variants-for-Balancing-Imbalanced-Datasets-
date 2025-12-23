# Spam Classification Project (Google Colab)

Project Overview

This project focuses on building and evaluating a machine learning–based system for Spam and Ham message classification using a real-world, highly imbalanced dataset.
The primary objective is to analyze the impact of data imbalance on classification performance and to assess how model training is affected under such conditions.

The implementation is carried out entirely using Google Colab, enabling seamless execution without the need for local environment setup. All preprocessing, model training, evaluation, and result visualization steps are fully reproducible through the provided notebook.

---

## Requirements
You only need:
- A Google account
- Internet connection
- Google Colab (no local Python installation required)

---

## Project Files
- `project(special_topic).ipynb` → Main Jupyter Notebook
- `spam.csv` → Dataset used for training and evaluation

---

## How to Run the Project on Google Colab

### **Step 1: Open Google Colab**
1. Go to: https://colab.research.google.com
2. Sign in using your Google account

---

### **Step 2: Upload the Notebook**

---

### **Step 3: Upload the Dataset**
1. In Colab, click the **folder icon** on the left panel
2. Click **Upload**
3. Upload:

Make sure the dataset is uploaded to the **root directory** of Colab.

---

### **Step 4: Verify Dataset Path**
The notebook assumes the dataset path is:

```python
df = pd.read_csv("spam.csv")

### **Step 5: Run the code**

1. Click **File → Upload notebook**
2. Upload the file:
