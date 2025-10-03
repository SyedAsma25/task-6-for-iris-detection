# 💠 Iris Species Predictor: A K-Nearest Neighbors Approach

A machine learning project to accurately predict Iris flower species from petal and sepal dimensions.

---

### ✨ **Project Goal**

The primary objective is to develop and evaluate a K-Nearest Neighbors (KNN) classifier to distinguish between three species of Iris flowers. This project demonstrates key machine learning concepts, including hyperparameter tuning and model visualization.

### 🔬 **Methodology**

The analysis follows a structured pipeline:
1.  **Data Ingestion & Cleaning**: The dataset is loaded and prepared for modeling.
2.  **Feature Scaling**: `StandardScaler` is applied to normalize features, which is crucial for distance-based algorithms like KNN.
3.  **Hyperparameter Tuning**: We iterate through various values of 'K' to find the one that yields the highest accuracy on the test set.
4.  **Model Training & Evaluation**: The final KNN model is trained and its performance is assessed through a confusion matrix and classification report.

### 📈 **Performance Highlights**

The final model demonstrates excellent predictive power, correctly classifying the vast majority of test samples.

* **Optimal Number of Neighbors (K):** Found via the Elbow Method.
* **Prediction Accuracy:** Achieved a high accuracy score, indicating a strong model.

![Confusion Matrix](https://placehold.co/450x350/2c5282/ffffff?text=Confusion+Matrix)
> The confusion matrix shows a low number of misclassifications, confirming the model's reliability.

### 🗺️ **Decision Boundary Visualization**

To provide an intuitive understanding of the model's predictive behavior, we visualized the decision boundaries. This plot illustrates the regions in the feature space where the model would predict each of the three Iris species.

![KNN Decision Boundaries](https://placehold.co/600x400/718096/ffffff?text=Classifier+Decision+Regions)

### 🚀 **Getting Started**

**Prerequisites:**
* Python 3.7+
* Jupyter Notebook or JupyterLab

**Installation:**
```sh

# Install the required packages
pip install pandas scikit-learn matplotlib seaborn
