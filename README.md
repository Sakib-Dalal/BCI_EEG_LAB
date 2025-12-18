# 🧠 BCI_EEG_LAB

### **Repository Overview**
**BCI_EEG_LAB** is a comprehensive laboratory and codebase designed for the analysis, processing, and classification of Electroencephalography (EEG) signals for Brain-Computer Interface (BCI) applications. This project serves as a framework for experimenting with brain signal data, implementing machine learning models, and developing BCI systems.

### **Key Features**
*   **EEG Signal Preprocessing**: Tools for noise reduction, artifact removal (EOG/EMG), bandpass filtering, and epoching raw EEG data.
*   **Feature Extraction**: Implementation of common extraction techniques such as Power Spectral Density (PSD), Common Spatial Patterns (CSP), and Wavelet Transforms.
*   **Machine Learning Classification**: Application of ML algorithms (e.g., SVM, Random Forest) and Deep Learning models (e.g., CNNs, EEGNet) to classify mental states (e.g., Motor Imagery, P300).
*   **Visualization**: Jupyter notebooks for visualizing raw signals, time-frequency maps, and topographic brain maps.
*   **Dataset Handling**: Scripts to load and format standard BCI datasets (e.g., BCI Competition IV, PhysioNet).

### **Tech Stack**
*   **Language**: Python 🐍
*   **Signal Processing**: MNE-Python, SciPy, NumPy
*   **Machine Learning**: Scikit-learn, TensorFlow / PyTorch
*   **Data Manipulation**: Pandas
*   **Visualization**: Matplotlib, Seaborn

### **Getting Started**
1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Sakib-Dalal/BCI_EEG_LAB.git
    ```
2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run Experiments**:
    Navigate to the notebooks folder to explore EEG analysis tutorials or run the main scripts to train BCI models.

### **Purpose**
This repository aims to bridge the gap between raw neuroscience data and practical AI applications, providing a playground for researchers and developers to explore the intersection of Neuroscience and Artificial Intelligence.