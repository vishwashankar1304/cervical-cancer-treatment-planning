# Cervical Cancer Treatment Planner (Final Year Project)

This project is an AI-driven clinical tool designed to **analyze cervical cancer MRI scans and patient data** to assist doctors in treatment planning. It combines **Vision Transformers (ViT)**, **MedFormer**, and **ClinicalBERT** to extract insights from both images and patient metadata, while also using **Grad-CAM** for explainability to highlight tumor regions.

---

## 🚀 Project Status
- **Stage 1 (Completed):** Data preprocessing (image resizing, normalization, and clinical metadata structuring).
- **Stage 2 (In Progress):** Model training using ViT + MedFormer (image features) and ClinicalBERT (text features).
- **Stage 3 (Upcoming):** Integration of Grad-CAM for interpretability and website deployment.

---

## 🛠 Tech Stack
- **Python** (Google Colab for development)
- **PyTorch & Transformers** (for ViT, MedFormer, and ClinicalBERT)
- **Grad-CAM** (for model interpretability)
- **Pandas & OpenCV** (for preprocessing)

---

## 📂 Dataset
- 200 patient cases, each containing:
  - **4–5 MRI images per case** (`case001` to `case200`).
  - **metadata.xlsx** – Patient clinical details.
  - **imgtypes.xlsx** – Image filenames with type details.

*(Dataset is private and stored in Google Drive for research use.)*

---

## 📌 Current Features
- Preprocessed all MRI images (resized, normalized).
- Structured clinical and image metadata for each case.
- Set up Vision Transformer (ViT) backbone for image feature extraction.

---

## 🔜 Next Steps
- Train ViT + MedFormer on images.
- Extract ClinicalBERT embeddings for clinical text.
- Combine both into a hybrid model.
- Use Grad-CAM to highlight tumor regions.
- Deploy the system as a **web application**.

---

## 🖇 Repository Structure
