# 🕵️‍♂️ Crime Pattern Detection Using DBSCAN Clustering

This project uses **unsupervised machine learning** with **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to identify and visualize hidden patterns in crime datasets. It provides data preprocessing, clustering, and visualization functionalities to assist in strategic law enforcement and hotspot detection.

---

## 📊 Objective

The main objective is to:
- Detect **high-crime density zones** using geospatial clustering.
- Visualize crime trends in cities using **matplotlib**, **folium**, and **seaborn**.
- Support police departments or researchers with automated cluster analysis of crime reports.

---

## 🧠 Technologies Used

- **Python 3**
- **scikit-learn** (for DBSCAN clustering)
- **pandas**, **NumPy** (data preprocessing)
- **matplotlib**, **seaborn** (data visualization)
- **folium** (interactive maps)
- **Jupyter Notebook**

---

## 🧾 Features

- Clean and preprocess real-world crime datasets.
- Apply DBSCAN clustering to detect crime zones.
- Generate interactive visual maps with **folium**.
- Plot heatmaps and cluster scatterplots.
- Automatically detect outliers and anomalies.

---

## 📁 Folder Structure

```bash
Crime-Pattern-Detection-Using-DBSCAN-Clustering/
│
├── crime_data.csv                 # Sample dataset (replace with real data)
├── CrimePatternDetection.ipynb   # Main Jupyter notebook
├── clustering.py                 # Clustering logic (optional)
├── requirements.txt              # Required libraries
└── README.md                     # This file
