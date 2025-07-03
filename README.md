# AI-ML-TASK-7
# Breast Cancer Classification using SVM

This project uses Support Vector Machines (SVM) to classify tumors as **malignant (1)** or **benign (0)** using breast cancer data from a CSV file.
-> Load & Clean Data
   - Read CSV file  
   - Drop unwanted columns (e.g., `id`, `Unnamed: 32`)  
   - Convert `diagnosis` to binary (M → 1, B → 0)  
   - Scale features

-> Train SVM Models
   - SVM with **linear** kernel  
   - SVM with **RBF** kernel

->Visualize Decision Boundary
   - Apply PCA to reduce data to 2D  
   - Plot decision boundary with colored regions

-> Tune Hyperparameters
   - Use GridSearchCV to find best `C` and `gamma` values

-> Evaluate Model
   - Accuracy score  
   - 5-fold Cross-validation average



