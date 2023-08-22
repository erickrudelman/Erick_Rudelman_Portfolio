---
date: 2023-08-08T11:01:59-04:00
description: "Breast Cancer Detection App"
featured_image: "/images/breast_cancer.jpg"
tags: []
title: "Project I: Breast Cancer Detection App"
---
The provided Python code showcases an interactive web application built using the Streamlit library. This application serves a significant purpose in breast cancer prediction and data visualization. It combines elements of machine learning, data visualization, and user interaction to provide valuable insights into breast cancer data.

**Breast Cancer Prediction and Data Visualization App**

Function and Purpose:
This Streamlit app serves as a versatile tool to predict whether a given tumor is malignant or benign based on user-input tumor parameters. Additionally, the app empowers users to visually explore the breast cancer dataset through interactive data visualization, fostering a better understanding of the data distribution and its implications.

**App Workflow and Features:**

**Input Tumor Parameters:**
The app begins by displaying a title and author's name on the main page. On the sidebar, users are presented with an array of input fields corresponding to various tumor parameters. These parameters include features like radius, texture, and smoothness, which are pivotal in diagnosing breast tumors.

**User Input Features:**
Upon interacting with the sidebar, users can input numerical values for each tumor parameter. The app dynamically updates to reflect user input in real-time.

**Display User Input:**
The app proceeds to display the user's input parameters, allowing users to verify their choices and ensuring transparency in the prediction process.

**Breast Cancer Dataset Information:**
In this section, the app provides essential information about the breast cancer dataset, including the number of samples, features, and class labels (benign or malignant). This establishes context for users regarding the dataset's scale and composition.

**Display Dataset Overview:**
The app generates a comprehensive DataFrame overview of the breast cancer dataset, presenting a concise yet detailed snapshot of the data.

**Display Column Names:**
Users are presented with the column names of the breast cancer dataset, helping them grasp the significance of each feature in the context of the diagnosis.

**Model Prediction:**
Leveraging a RandomForest classifier, the app takes user-input parameters and predicts whether the corresponding tumor is benign or malignant. The prediction, along with prediction probabilities, is showcased, providing valuable insights into the diagnostic outcome.

**Data Visualization:**
One of the highlights of the app is its data visualization aspect. Users can select a specific feature (e.g., "mean radius") and observe its distribution through an interactive histogram. This visualization aids users in identifying patterns and trends within the data.

**Data Visualization Explanation:**
The app provides an explanation of the histogram visualization, elucidating concepts such as x-axis values (feature values), y-axis frequency (data points count), and the Kernel Density Estimation (KDE) curve.

**Conclusion and Interpretation:**
The app concludes by offering an interpretation of the histogram visualization. It guides users in understanding the distribution's characteristics, including peak points, skewness, and the presence of outliers.

**Data Science Techniques and Libraries Applied:**

**Machine Learning (ML):** The RandomForest classifier is employed for tumor prediction based on input parameters. This ML technique contributes to diagnostic decision-making by predicting benign or malignant classifications.

**Data Visualization:** Various visualization techniques are used, including histograms and KDE curves, to provide a visual representation of the data's distribution. This aids users in exploring and understanding the dataset more intuitively.

**Libraries:** The app harnesses libraries such as streamlit, pandas, numpy, matplotlib, seaborn, and plotly to create an interactive user interface, manipulate data, visualize insights, and create plots.
In essence, this Streamlit application marries machine learning and data visualization to offer a user-friendly platform for both medical professionals and curious individuals to predict breast tumor classifications and gain insights into the underlying data patterns. It embodies a powerful blend of technology and data-driven analysis to contribute to medical diagnosis and awareness.

[Link to GitHub Repository](https://github.com/rudicr/data_science_projects/blob/Data-Science-Projects/breast_cancer_detection_app.py)
