### **README: Hyperspectral ML for Mycotoxin Prediction**  

## **Project Overview**  
This project predicts **DON (vomitoxin) concentration** in corn samples using **hyperspectral imaging data** and **machine learning models**. The workflow includes **data preprocessing, dimensionality reduction (PCA, t-SNE), model training (Random Forest, XGBoost, Neural Networks), and performance evaluation (MAE, RMSE, R² Score).**  

## **Installation**  
To install the required dependencies, run:  
```bash
pip install -r requirements.txt
```  

## **Dataset Description**  
- **Features**: Spectral reflectance values across 448 wavelength bands.  
- **Target Variable**: `vomitoxin_ppb` (DON concentration in corn).  

## **Workflow**  
🔹 **Data Preprocessing** – Handling missing values, scaling features.  
🔹 **Exploratory Data Analysis (EDA)** – Visualizing spectral trends and correlations.  
🔹 **Dimensionality Reduction** – PCA & t-SNE for feature extraction.  
🔹 **Model Training** – Comparing **Random Forest, XGBoost, and MLP Neural Network**.  
🔹 **Model Evaluation** – Using **MAE, RMSE, and R² Score** to assess accuracy.  

## **How to Run**  
1. Clone the repository:  
   ```bash
   git clone [repository_url]
   ```  
2. Navigate to the project folder:  
   ```bash
   cd project_folder
   ```  
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```  
   Open and execute `ml_intern_assignment.ipynb`.  

## **Results & Insights**  
- PCA & t-SNE effectively reduced feature dimensions while preserving variance.  
- The best-performing model was **[Insert Best Model After Running]**, achieving **[Best R² Score]**.  
- Model predictions were visualized using scatter plots for **actual vs. predicted** DON levels.  

## **Deliverables**  
📑 **Jupyter Notebook**: `ml_intern_assignment.ipynb`  
📘 **Report**: `ML_Intern_Report.pdf`  
📂 **README.md**  


🚀 **Future Improvements**: Optimize hyperparameters, explore transformer-based models, deploy via Streamlit for real-time predictions.
