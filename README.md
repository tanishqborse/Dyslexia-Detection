# 🧠 Dyslexia Detection Using Machine Learning

This repository contains a machine learning-based solution for detecting dyslexia using behavioural and cognitive data. **Dyslexia Detection** leverages advanced machine learning models to identify dyslexic patterns in individuals, aiding in early diagnosis and intervention. The project demonstrates how data-driven approaches can enhance diagnostic processes, potentially providing more accurate and faster results than traditional methods.

## 📜 Project Overview


Dyslexia is a neurological disorder which affects about 5-10% of the total population which amounts to about 700 million worldwide. It is a language-based learning disability. Its symptoms are different for different people. It generally affects how people read and write. Among the total population of people having difficulties with reading, writing, speaking and spelling, about 70-80% suffer from some level of dyslexia. Dyslexia is generally defined by a spectrum of difficulties. The current methods of detecting dyslexia is based on a series of reading, writing and speaking tests. The drawback of this system of testing is that they are quite expensive and not available everywhere. We developed a technique for detecting dyslexia based on eye tracking using unsupervised machine-learning classification techniques. There has already been some research has been done in the domain of detecting this condition by analysing eye-tracking data. We took some inspiration from a study titled: "Screening for Dyslexia Using Eye Tracking during Reading", conducted by Nilsson Benfatto and his group. Their work relied on extracting features from the eye-tracking data. They developed a classification algorithm based on a supervised learning method. The data that they worked on was available online and we used the same data for building our classifier. The data consisted of eye-tracking readings of 98 dyslexic candidates and 88 non-dyslexic/control candidates. We wanted to approach the problem from a non-supervised learning perspective. We were curious to see if we could differentiate Dyslexic from non-dyslexic based on the data itself and not relying on the existing labels to train our classifier. We developed a unique approach to analyze eye-tracking data based on the nature of the frequency spectrum.

---
## 🎯 Key Objectives

- **Early Detection**: Detect dyslexia in individuals at an early stage through behavioural and cognitive analysis.
- **Accuracy**: Provide high-accuracy predictions using advanced machine learning models.
- **Scalability**: Build a scalable solution that can handle data from multiple individuals and environments.

---
## 🚀 Highlights:

- We used the Eye tracking data set for two groups: control and Dyslexic. Since the reading speed of each person is different, the samples in the data set have varying lengths.
- We used a binning approach to tackle the unequal lengths of data in two approaches:
- Binning on Spectral Data: To get equal-length vectors which encompass all temporal information.
- Short time Fourier Transform: Binning on temporal data and then considering the frequency components to evaluate the temporal significance of certain spectral values.
- PCA: Principal Component Analysis on binned data to reduce the number of dimensions.
---

## 🛠️ Tools & Technologies

| Tool/Technology  | Description  |
| ---------------- | ------------ |
| ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) | Programming language used for data manipulation and model building. |
| ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white) | Data preprocessing and manipulation. |
| ![Scikit-learn](https://img.shields.io/badge/-Scikit_Learn-F7931E?logo=scikit-learn&logoColor=white) | Machine learning model implementation and evaluation. |
| ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white) | Deep learning models for CNN implementation. |
| ![Matplotlib](https://img.shields.io/badge/-Matplotlib-000000?logo=matplotlib&logoColor=white) | Data visualization for insights and performance analysis. |
| ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) | Interactive environment for running experiments and training models. |

---

## 🚀 Future Scope

- **Multi-modal Data Integration**: Expand the solution to include audio processing and handwriting recognition to further improve dyslexia detection.
- **Real-time Detection**: Develop real-time dyslexia detection using live data from classrooms.
- **Mobile Application**: Build a mobile-based solution for educators and parents to easily screen children for dyslexia.

---


