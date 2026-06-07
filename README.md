# Task-2-Sankil
## 📊 Project 2: K-Nearest Neighbors (KNN) Classification

**File:** `decodelabs2.py`

### Overview
A complete **K-Nearest Neighbors (KNN)** classification pipeline using the Iris dataset. This project demonstrates supervised learning, data preprocessing, model selection, and performance evaluation.

### What It Does
1. **Loads & Explores Data**: Uses the famous Iris dataset (150 samples, 4 features, 3 species)
2. **Preprocessing**: Standardizes features (mean=0, variance=1) using StandardScaler
3. **Train-Test Split**: 80% training, 20% testing (randomized, seed=42)
4. **Hyperparameter Tuning**: Tests K values from 1-30 using the Elbow Method
5. **Model Training**: Trains KNN classifier with optimal K value
6. **Performance Evaluation**: Generates confusion matrix, F1 score, and classification report
7. **Prediction**: Demonstrates predicting new unseen samples

### Key Concepts Covered
- ✅ Feature scaling (StandardScaler)
- ✅ Train-test split & avoiding data leakage
- ✅ Model selection (finding optimal K)
- ✅ Evaluation metrics (F1 score, confusion matrix, classification report)
- ✅ Single sample prediction

### Requirements
```
numpy
pandas
matplotlib
seaborn
scikit-learn
```

### Usage
```bash
python decodelabs2.py
```

### Expected Output
- Dataset statistics (head, describe, species distribution)
- Elbow curve plot (K vs Error Rate)
- Confusion matrix heatmap
- F1 score and detailed classification report
- Prediction for a new flower sample

### Output Example
```
Optimal K: 5
F1 Score: 0.9667
Predicted species: setosa
```

---
