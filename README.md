
# 🐦 **Echoes of Endangerment: Investigating the Rose-Crested Blue Pipit's Decline** 🌳

## **Overview**  
This repository documents a collaborative effort to analyze the decline of the 🐦 *Rose-Crested Blue Pipit* in the Boonsong Lekagul Wildlife Preserve. Conducted as part of Rowan University's **Information Visualization** course and aligned with the **VAST Challenge 2018 MC1**, this project combines 🗺️ geospatial mapping, 🎵 audio analysis, and 🤖 machine learning techniques to uncover potential environmental threats and species misclassifications.

**🎯 Objective:** Challenge Kasios Office Furniture's claims of environmental responsibility and investigate their potential role in the Pipit's decline.

---

## **🌟 Project Highlights**

### 🌍 **Geospatial and Data Analysis**  
- **📍 Location Mapping:**
  - Visualized bird call recording sites and migration routes using GeoPandas.
  - Identified the alleged industrial dumping site at coordinates **(148, 159)**.
- **📊 Data Validation:**
  - Cross-checked datasets from Mistford College and Kasios Office Furniture for anomalies.
  - Exposed suspicious inconsistencies in Kasios's claims.

---

### 🎵 **Audio Analysis**  
- **🎤 Preprocessing Audio:**
  - Cleaned and enhanced recordings using **Audacity** and **Librosa**.
  - Extracted key features like:
    - 📈 **Root Mean Square Energy (RMS)**
    - 🎼 **Chromagram Analysis**
    - 🎧 **Short-Time Fourier Transform (STFT)**
    - 🔊 **Spectral Centroid**
- **🧐 Spectrum Analysis:** Identified tonal and frequency patterns unique to the *Blue Pipit*.

---

### 📈 **Machine Learning Classification**  
- **🤖 Models Implemented:**
  - 🌲 **Random Forest**
  - 🤝 **K-Nearest Neighbors (KNN)**
  - 🌳 **Decision Trees**
  - 📊 **Gaussian Naive Bayes**
- **🏆 Key Results:**
  - **Random Forest** achieved the best accuracy, identifying several species misclassifications in Kasios’s data.
  - Highlighted suspicious recordings that contradict Kasios’s eco-friendly image.

---

### 📊 **Data Visualization**  
- **✨ Interactive Dashboards:**
  - Built **Tableau** dashboards to showcase bird call trends and geographic distributions.
- **📅 Temporal Patterns:**
  - Tracked *Blue Pipit* nesting and migration patterns, revealing a decline post-2015.

---

## **🔍 Research Methodology**

### 🧹 **Data Cleaning**
- Standardized `Vocalization Type` and `Audio Quality` using **OpenRefine**.
- Merged datasets and ensured consistency across sources.

### 📊 **Exploratory Analysis**
- **Geospatial Trends:** Mapped bird call recordings and migration routes.
- **Temporal Insights:** Visualized recording quality and call type distributions over time.

### 🎵 **Feature Engineering**
- Processed audio using:
  - 🌀 **FFT (Fast Fourier Transform)** for frequency analysis.
  - 🎼 **Chromagram** to analyze tonal structures.
  - 🔊 **Spectral Centroid** to measure sound intensity.

### 🤖 **Model Training**
- Trained on Mistford College's *AllBirds* dataset.
- Tested against Kasios's recordings to uncover misclassified data.

---

## **🌟 Key Findings**
1. **🚩 Data Anomalies:**  
   - Several recordings from Kasios were misclassified and did not match the *Rose-Crested Blue Pipit's* characteristics.
2. **🔍 Species Misclassification:**  
   - Machine learning models exposed mislabeled bird species in Kasios’s dataset.
3. **🌳 Environmental Disruption:**  
   - Geospatial and temporal trends suggest habitat disruption, likely linked to industrial activity.

---

## **🛠️ Technologies Used**
- **Data Cleaning:** OpenRefine 🧹  
- **Audio Analysis:** Audacity 🎤, Librosa 🎧  
- **Visualization:** Tableau 📊, Matplotlib 📈, Seaborn 🖼️  
- **Geospatial Mapping:** GeoPandas 🗺️  
- **Machine Learning:** Scikit-learn 🤖  
- **Development Platform:** Jupyter Notebook 📒  

---

## **💡 Conclusion**  
The findings expose significant inconsistencies in Kasios's claims and suggest their activities may be contributing to the *Rose-Crested Blue Pipit's* decline. By leveraging advanced analytics and machine learning, this project highlights the importance of ecological accountability and data-driven conservation efforts.

---

### **🚀 Ready to Explore?**
Dive into the file to explore:
- 🗺️ Maps of bird call locations and migration patterns.
- 🎵 Audio processing techniques and analysis scripts.
- 🤖 Machine learning models and classification results.

