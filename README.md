# Research Publications — Machine Learning | Natural Language Processing | Time-Series | Deep Learning | RNN/CNN | Decision Systems | Recommendation Systems

This repository contains my published and upcoming co-authored research publications (conference papers) along with a non-authored but research-contributed paper (published conference paper) across international journals like IEEE Xplore Digital Library and Elsevier Science Direct's Procedia Computer Science across supervised machine learning, NLP, time-series decision-making, and deep learning, with a strong focus on hands-on contributions in **model training, validation, experimentation, and performance evaluation**. The work spans real-world applications including **EV smart charging optimization**, **imbalance-aware offensive language detection**, and **handwritten Hindi word recognition using deep CNN–RNN architectures**, alongside an ultrasonic sensor-array based object classification study.

✅ **Co-authored papers (2, 3, 4):**
- Decision-Making Approach for Smart Charging of Electric Vehicles (IEEE)
- Offensive Language Detection in Social Media Text Using Imbalance-Aware NLP Models (Elsevier - Upcoming)
- Handwritten Hindi Word Recognition Using Deep CNN–RNN Architectures (IEEE - Upcoming)

📌 **Research apprenticeship contribution (non-coauthor):**
- Object Shape Classification Using 4×4 Ultrasonic Sensor Array (IEEE)

---

## Publications (with My Contributions)

### 1) Object Shape Classification Using 4×4 Ultrasonic Sensor Array (IEEE) — Research Apprenticeship Contribution (Non-Coauthor)
**Venue:** 2024 4th International Conference on Technological Advancements in Computational Sciences (ICTACS)  
**Location:** Tashkent, Uzbekistan | **Dates:** 13–15 Nov 2024  
**IEEE Xplore:** Added 21 Jan 2025  
**DOI:** 10.1109/ICTACS62700.2024.10840499  
**PDF:** `papers/2024_ICTACS_Object_Shape_Classification_Ultrasonic_Array.pdf`

**What the paper solves:**  
This research builds an ultrasonic sensor-array system inspired by biological echolocation for real-time object shape recognition using machine learning models on time-of-flight (ToF) signals.

**My Contribution (Syed Mohammad Bilal — DTU Research Apprenticeship):**
- Developed and evaluated the supervised ML pipeline for real-time object shape classification using a **4×4 ultrasonic sensor array**.
- Structured the dataset from **3,100+ multi-sensor ToF samples**, enabling reliable model training and benchmarking.
- Trained and compared **XGBoost, Random Forest, MLP (ANN), and SVM** using multi-metric evaluation (**accuracy, precision, recall, F1-score**).
- Finalized **XGBoost** as the best-performing model, achieving **99.05% accuracy** and **99.25% F1-score**.
- Validated strong generalisation on **previously unseen object geometries**, achieving **96–97% accuracy**.
- Supported feature importance + multicollinearity analysis and contributed to a noise-reduction preprocessing pipeline, improving **signal-to-noise ratio (SNR) by 15.35 dB**, strengthening real-time inference robustness.

**Authorship Note:**  
This work was completed as part of a department-led research project during my DTU apprenticeship. I contributed to the ML pipeline development and evaluation; however, I am **not listed as a co-author** on the final IEEE publication.

*Tech/Tools: Python • Supervised ML • XGBoost • Random Forest • SVM • MLP (ANN) • Feature Importance • Multicollinearity Analysis • Noise Reduction • Model Evaluation (Accuracy/Precision/Recall/F1)*

---

### 2) Decision-Making Approach for Smart Charging of Electric Vehicles (IEEE) — Co-author
**Venue:** IEEE Transportation Electrification Conference (ITEC India 2021)  
**Presented:** 16–19 Dec 2021 | **IEEE Xplore:** Published 9 Nov 2022  
**DOI:** 10.1109/ITEC-India53713.2021.9932481  
**Model Performance:** **96.2% training accuracy**, **98.8% testing accuracy**  
**PDF:** `papers/2021_ITEC_India_EV_Smart_Charging_Decision_Making.pdf`

**What the paper solves:**  
This paper proposes a decision-making framework for EV smart charging using multi-parameter time-series inputs (e.g., demand, charging efficiency, environment-driven factors) to support optimized charging decisions.

**My Contribution (Syed Mohammad Bilal — Co-author):**
- Built and validated a supervised ML-based smart charging decision framework using time-series features.
- Performed dataset preparation, sampling, and alignment across multi-source parameters to ensure modeling consistency.
- Trained and tested a Decision Tree model achieving **96.2% train** and **98.8% test accuracy**, supporting reliable decision logic.
- Contributed to experimentation, analysis, and final research conclusions for publication.

*Tech/Tools: Python • Supervised ML • Decision Trees • Model Training & Validation • Dataset Alignment • Time-Series Analysis*

---

### 3) Offensive Language Detection in Social Media Text Using Imbalance-Aware NLP Models (Elsevier - Upcoming) — Co-author
**Venue:** International Conference on Machine Learning and Data Engineering (ICMLDE 2025)  
**Publication:** Elsevier ScienceDirect (Procedia Computer Science) — expected 2026  
**Manuscript:** `papers/2025_ICMLDE_Offensive_Language_Detection_Manuscript.pdf`

**What the paper solves:**  
This work focuses on offensive language detection in social media text using imbalance-aware NLP models to improve reliability on skewed datasets and enhance minority-class detection.

**My Contribution (Syed Mohammad Bilal — Co-author):**
- Built NLP preprocessing and supervised text classification pipeline for offensive language detection.
- Applied imbalance-aware training strategies to improve detection of low-frequency offensive classes.
- Evaluated models using precision/recall-focused metrics to optimize real-world moderation performance.
- Contributed to experimentation, result interpretation, and manuscript-ready insights.

*Tech/Tools: Python • NLP • Text Classification • Imbalanced Learning • Precision/Recall Optimization • Model Evaluation*

---

### 4) Handwritten Hindi Word Recognition Using Deep CNN–RNN Architectures (IEEE - Upcoming) — Co-author
**Venue:** IEEE Delhi Section Conference (DELCON 2025, Region 10)  
**IEEE Xplore:** Expected 2026  
**Manuscript:** `papers/2025_DELCON_Handwritten_Hindi_Word_Recognition_Manuscript.pdf`

**What the paper solves:**  
This paper explores handwritten Hindi word recognition using deep CNN–RNN architectures, combining CNN-based feature extraction with RNN-based sequence modeling to improve OCR/HTR performance under handwriting variability.

**My Contribution (Syed Mohammad Bilal — Co-author):**
- Designed and trained deep CNN–RNN architectures for handwritten Hindi word recognition.
- Worked on preprocessing and training workflows to improve robustness across handwriting styles.
- Evaluated model performance and contributed to experiment-backed improvements for final publication.
- Supported research write-up and technical validation for conference submission.

*Tech/Tools: Python • Deep Learning • CNN • RNN • OCR/HTR • Image Preprocessing • Model Training & Evaluation*

---

## Tech Stack
Python • Supervised ML • NLP • Time-Series Analysis • Decision Trees • XGBoost • Deep Learning (CNN/RNN) • Model Training & Validation • Imbalanced Learning
