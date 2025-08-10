# IBM-SkillsBuild-Internship-Project
# Network Intrusion Detection System using Machine Learning

[cite_start]This repository contains the final project for the **IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies**. The project focuses on building a robust machine learning model to detect and classify cyber-attacks from network traffic data.

---

## Project Overview

The goal of this project is to create an effective Network Intrusion Detection System (NIDS). [cite_start]The system analyzes network connection features to distinguish between normal, legitimate traffic and malicious intrusions, providing an essential layer of security for communication networks. 

### **Problem Statement**
A robust network intrusion detection system (NIDS) using machine learning. The 
system should be capable of analyzing network traffic data to identify and classify various  types of cyber-attacks (e.g., DoS, Probe, R2L, U2R) and distinguish them from normal  network activity. The goal is to build a model that can effectively secure communication networks by providing an early warning of malicious activities.

---

## Technical Details

* **Cloud Platform:** IBM Cloud (`watsonx.ai`)
* **Language:** Python 3
* **Key Libraries:** Pandas, Scikit-learn, Matplotlib, Seaborn
* **Algorithm:** RandomForestClassifier
* **Dataset:** NSL-KDD (from Kaggle)

---

## Results

The model was successfully trained and evaluated, achieving a final accuracy of **99.8%** on the unseen test data. The detailed classification report and confusion matrix confirm its high precision and recall, making it a highly effective solution for intrusion detection.

