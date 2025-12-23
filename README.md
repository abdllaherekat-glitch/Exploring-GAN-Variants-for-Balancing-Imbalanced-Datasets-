# Exploring GAN Variants for Balancing Imbalanced Datasets (Google Colab)

## Objective
This project aims to deepen the understanding of **Generative Adversarial Networks (GANs)** by
implementing and comparing a **Vanilla GAN** with an advanced variant, namely the
**Wasserstein GAN (WGAN)**, to address the challenge of **imbalanced datasets**.

Synthetic data is generated for the **minority class only** using both GAN models. The generated
samples are then used to balance the original dataset, and the impact on **classification
performance** is evaluated using standard machine learning metrics.

---

## Project Overview
The project investigates how different GAN architectures contribute to improving classification
results when training data suffers from severe class imbalance. Three experimental scenarios
are considered:

1. Training a classifier on the **original imbalanced dataset**
2. Training a classifier on a dataset balanced using **Vanilla GAN–generated samples**
3. Training a classifier on a dataset balanced using **WGAN–generated samples**

The performance across these scenarios is compared to analyze improvements in minority-class
recognition and overall model robustness.

---

## GAN Models Used
- **Vanilla GAN**: Used as a baseline generative model for minority class data augmentation.
- **Wasserstein GAN (WGAN)**: An advanced GAN variant designed to improve training stability
  and generate higher-quality synthetic samples for imbalanced data.

---

## Repository Contents
- `project(special_topic).ipynb` — Main Jupyter Notebook (Google Colab compatible)
- `spam.csv` — Imbalanced Spam/Ham dataset

---

## How to Run the Project on Google Colab

### Step 1: Open Google Colab
Go to: https://colab.research.google.com  
Sign in using your Google account.

---

### Step 2: Open the Notebook
**Option A (Recommended – from GitHub):**
1. Click **File → Open notebook**
2. Go to the **GitHub** tab
3. Paste the repository link
4. Open `project(special_topic).ipynb`

**Option B (Upload manually):**
1. Click **File → Upload notebook**
2. Upload `project(special_topic).ipynb`

---

### Step 3: Upload the Dataset
1. Click the **Files** icon on the left panel
2. Click **Upload**
3. Upload `spam.csv`

⚠️ Ensure the filename remains exactly `spam.csv`.

---

### Step 4: Run the Notebook
1. Click **Runtime → Run all**
2. Wait for all cells to finish execution

The notebook will automatically:
- Analyze dataset imbalance
- Train Vanilla GAN and WGAN on the minority class
- Generate synthetic samples
- Balance the dataset
- Train and evaluate the classifier
- Display metrics and visualizations

---

## Evaluation Metrics
The classification performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix  
(Optional: AUC-ROC)

---

## Notes
- The entire project runs on **Google Colab** with no local setup required.
- Results are fully reproducible using the provided notebook and dataset.

---

## Author
Student Project — Special Topics in Artificial Intelligence
