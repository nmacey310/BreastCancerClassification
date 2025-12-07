Breast Cancer Classification Project

Objective
Classify breast tumors as malignant or benign using ML and DL techniques.

Dataset
Source Breast Cancer Wisconsin Diagnostic dataset (sklearn)
- Structure: 569 samples, 30 numerical features
- Target: Tumor type (malignant=0, benign=1)

Methodology
1. Exploratory Data Analysis (EDA):
   - Checked for missing values
   - Visualized distributions, correlations, and class balance
2. Machine Learning:
   - Random Forest, SVM
   - Evaluated using accuracy, confusion matrix, ROC
3. Deep Learning:
   - Feed-forward neural network
   - Early stopping and learning rate tuning
4. Hyperparameter Tuning:
   - Grid search for RF and learning rate tuning for NN

Results
- VM Accuracy: 98%
- Random Forest Accuracy:95.6%
- Neural Network Accuracy: 95.6%
- Visualizations: ROC curves, confusion matrices, feature importance

Conclusion
Traditional ML algorithms like SVM and Random Forest performed best for this structured dataset, while deep learning achieved competitive accuracy but requires larger datasets for optimal performance.

