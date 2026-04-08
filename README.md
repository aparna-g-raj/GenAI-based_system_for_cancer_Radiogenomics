# GenAI-Based System for Cancer Radiogenomics

This project presents a multi-modal cancer analysis system that integrates medical imaging, radiomics, clinical data, and genomic (RNA-seq) data to improve cancer understanding and interpretability using Explainable AI.

---

## 🔍 Key Features

* CT Image Processing and Tumor Segmentation using AIM annotations
* Radiomics Feature Extraction (shape, texture, intensity)
* RNA-Seq Gene Analysis and Feature Selection
* Machine Learning Model (Random Forest) for prediction
* Explainable AI:

  * SHAP for gene-level interpretation
  * Grad-CAM for tumor region visualization
* Biological Validation:

  * Pathway-based gene analysis to ensure biological relevance

---

## 📂 Dataset Used

This project utilizes the **NSCLC Radiogenomics Dataset**, a publicly available dataset that combines imaging, clinical, and genomic data for Non-Small Cell Lung Cancer (NSCLC).

### Dataset Components:

* **CT Images (DICOM format)**
  Used for tumor visualization and radiomics feature extraction

* **AIM Annotations**
  Provide tumor location and segmentation information

* **Radiomics Features**
  Precomputed features such as tumor volume, texture, and shape

* **Clinical Data**
  Includes patient information such as age, gender, smoking status, and survival

* **RNA Sequencing Data (RNA-Seq)**
  Contains gene expression profiles for each patient

##  Workflow

1. CT images → Tumor localization → Radiomics features
2. RNA-seq data → Gene processing → SHAP importance
3. Clinical + Radiomics + Genomics → Model prediction
4. Explainability + Biological pathway validation

---

##  Output

* Patient-specific prediction
* Tumor visualization (Grad-CAM)
* Top influencing genes (SHAP)
* Biological interpretation (pathway mapping)

---

## Objective

To build an interpretable AI system that not only predicts cancer outcomes but also explains decisions using both imaging and genomic insights.

---

## Dataset Drive link:
https://drive.google.com/drive/folders/1afBNG-6-ifrm6Qpccd3im_5RBf5h44lh?usp=drive_link
