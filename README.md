# 🧠 MedVision - Medical Research Automation Platform

[![Open in GitHub](https://img.shields.io/badge/GitHub-Repo-blue?logo=github)](https://github.com/Nadaaaaaaaaaaaaaaaaaa/MedicalVision)
[![Demo Video](https://img.shields.io/badge/📺-Demo_Video-red)](https://drive.google.com/file/d/1z5cbp8tV79wsfxuc33Z6Ud1js6intV-O/view?usp=drive_link)
[![Download Project](https://img.shields.io/badge/📦-Download_Full_Project-green)](https://drive.google.com/file/d/13Ly_4l5KmrfM12r_rSIWVnwoZbE8zaZC/view?usp=sharing)

**Web-based platform for end-to-end medical data processing**  
*Supports tabular data & medical images with experiment tracking*

---

## 🌟 Features
| Category              | Capabilities                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| **Data Import**       | CSV/Excel/DICOM                                                    |
| **Visualization**     | 3D slicers, histograms, layer fusion                                      |
| **Preprocessing**     | Auto-normalization, skull-stripping, patch extraction                     |
| **Model Training**    | U-Net, Inception hybrids, AutoML configs                                  |
| **Evaluation**        | Dice score, ROC curves, confusion matrices                               |
| **Collaboration**     | Exportable reports, version comparisons                                   |

---

## 🎥 Interactive Demo
[![MedVision Demo](https://img.shields.io/badge/▶️-Watch_Full_Demo-red)](https://drive.google.com/file/d/1z5cbp8tV79wsfxuc33Z6Ud1js6intV-O/view?usp=drive_link)
*(Click to see live preprocessing + tabular data treatment demo)*

---

---

## 📊 Tech Stack
| Component       | Technology Stack                                                                 |
|----------------|---------------------------------------------------------------------------------|
| **Frontend**   | React + Redux, Three.js (3D), Plotly.js                                         |
| **Backend**    | Flask, Celery (async tasks), OpenCV/PyDICOM                                     |
| **AI Models**  | TensorFlow/Keras (3D U-Net), Scikit-learn (tabular)                            |
| **Database**   | MySQL (relational), MinIO (DICOM storage)                                      |

---

## 📂 Project Download
[![Download](https://img.shields.io/badge/Google_Drive-Download_Complete_Project-blue?logo=google-drive)](https://drive.google.com/file/d/13Ly_4l5KmrfM12r_rSIWVnwoZbE8zaZC/view?usp=sharing)  

---

## 🚀 Quick Deployment
### 1-Click Setup (Docker)
```bash
docker-compose -f docker-compose.prod.yml up --build
