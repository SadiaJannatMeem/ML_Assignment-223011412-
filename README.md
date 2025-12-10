# Breast Cancer KNN & K-Means Assignment

## Description
KNN classification and K-Means clustering on Breast Cancer dataset to classify tumors as malignant (M=1) or benign (B=0).

## Steps
1. Load dataset from Google Drive
2. Drop unnecessary columns (`id`, `Unnamed: 32`)
3. Encode diagnosis (M→1, B→0)
4. Min-Max normalization
5. Split train/test (80/20)
6. Apply K-Means clustering (k=2)
7. Train KNN classifier (k=5)
8. Evaluate Accuracy, Precision, Recall, F1-score

## Results
- Accuracy: 0.9649  
- Precision: 0.9535  
- Recall: 0.9535  
- F1-score: 0.9535
