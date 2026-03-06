<p align="center">

# 🌍⛏️  Mineral Prospectivity Mapping using GeoAI

### Machine Learning • Economic Geology • Mineral Exploration • GeoAI

</p>

---

## 📌 Project Overview

Mineral deposits rarely occur randomly. Their formation is strongly controlled by geological structures, hydrothermal alteration, host rock composition, and geochemical anomalies. Understanding these geological relationships is a fundamental goal of mineral exploration.

This project explores how **machine learning can assist geological interpretation** by highlighting areas that may show higher mineral prospectivity. The goal is not to claim mineral discovery, but to demonstrate how geological indicators can be integrated within a simple data-driven framework.

The workflow combines geological reasoning with a **Random Forest classification model**, simulating an early-stage exploration analysis commonly used in academic research and mineral exploration studies.

---

## 🎯 Project Objectives

• Demonstrate how geological indicators influence mineral prospectivity  
• Apply machine learning to evaluate mineral favorability  
• Visualize mineral potential using prospectivity heatmaps  
• Identify the most influential geological factors controlling predictions  

---

## 🪨 Geological Indicators Used

The model incorporates several geological proxies commonly used in mineral exploration:

**Distance to Fault (km)**  
Structural proximity often controls hydrothermal fluid flow and mineral deposition.

**Fault Influence Factor**  
Represents the exponential decay of hydrothermal influence away from major structures.

**Alteration Index**  
Acts as a proxy for hydrothermal alteration intensity around mineral systems.

**Geochemical Anomaly Strength**  
Represents enrichment of elements commonly associated with mineralization.

**Lithology (Host Rock Type)**  
Different rock types host different mineral systems and influence mineral potential.

These features were selected for their **geological meaning rather than purely mathematical convenience**.

---

## 🧠 Modeling Approach

A **Random Forest machine learning classifier** was used to estimate mineral prospectivity.

Workflow steps include:

• Dataset generation based on geological parameters  
• Lithology encoding for categorical geological variables  
• Model training using Random Forest classification  
• Cross-validation using **Stratified K-Fold validation**  
• Evaluation using **Precision–Recall analysis**

Precision–Recall metrics are particularly useful when analyzing **rare events**, such as mineral deposits.

---

## 📊 Model Evaluation

The model performance was evaluated using a **Precision–Recall Curve**, which measures the ability of the model to identify mineralized zones while reducing false predictions.

<p align="center">

![Precision Recall Curve](precision_recall_curve_mineral_model.png)

</p>

---

## 📈 Feature Importance Analysis

Feature importance analysis highlights which geological indicators most strongly influence mineral prospectivity predictions.

<p align="center">

![Feature Importance](feature_importance_mineral_model.png)

</p>

---

## 🗺️ Mineral Prospectivity Map

A prospectivity heatmap was generated to visualize how mineral potential changes with structural proximity and alteration intensity.

<p align="center">

![Mineral Prospectivity Map](mineral_prospectivity_map.png)

</p>

Bright regions indicate zones where geological conditions become more favorable for mineralization under the modeled scenario.

---

## ⚠️ Important Note

This project **does not claim mineral discovery**.

It is intended as an **academic demonstration** showing how geological reasoning and machine learning can be integrated during early-stage mineral exploration studies.

Real mineral exploration requires integration of:

• Field mapping  
• Geophysical surveys  
• Geochemical sampling  
• Drilling data  
• Geological interpretation  

---

## 🚀 Future Scope

With real geological datasets, this workflow could be extended by integrating:

• GIS-based structural datasets  
• Remote sensing alteration mapping  
• Multi-element geochemical datasets  
• Spatial mineral systems modeling  
• Advanced geospatial machine learning techniques

---

## 🛠 Tools & Technologies

Python  
NumPy  
Pandas  
Scikit-Learn  
Matplotlib  

---

## 📚 References

Bonham-Carter, G. F. (1994)  
*Geographic Information Systems for Geoscientists.*

Carranza, E. J. M. (2009)  
*Geochemical Anomaly and Mineral Prospectivity Mapping.*

Breiman, L. (2001)  
*Random Forests — Machine Learning Journal.*

---

<p align="center">

## 👤 Author

**Bikrant Kumar Mishra**  
B.Sc. Geology  

GeoAI • Machine Learning • Mineral Exploration • Earth System Analysis

</p>
