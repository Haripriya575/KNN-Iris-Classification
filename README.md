# KNN-Iris-Classification
K-Nearest Neighbors (KNN) classification on the Iris dataset, including data preprocessing, model training with different K values, accuracy evaluation, and visualization of decision boundaries.
Overview
This project implements the **K-Nearest Neighbors (KNN)** algorithm to classify the Iris dataset into three species. The workflow includes:
- Loading and exploring the dataset
- Data normalization using `StandardScaler`
- Training KNN with multiple K values
- Selecting the best K for optimal accuracy
- Evaluating performance with metrics
- Visualizing decision boundaries (for first two features)

---

 Dataset
- **Name**: Iris Dataset (from `sklearn.datasets`)
- **Features**:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- **Target**: Iris species (Setosa, Versicolor, Virginica)

---

 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

---

 Steps Performed
1. Imported libraries & loaded dataset
2. Scaled features using `StandardScaler`
3. Split data into train and test sets
4. Trained KNN models for K=1 to 10
5. Selected best K based on accuracy
6. Evaluated with:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
7. Visualized decision boundaries (first two features)

---

 Results
- **Best K Value**: _Varies based on random split_
- **Test Accuracy**: ~97% (with best K)
- **Classification Report**:
  - High precision and recall across all classes

---

 Visualizations
- Confusion matrix heatmap
- Decision boundaries (first two features)

---

 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/KNN-Iris-Classification.git

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Run the notebook
jupyter notebook knn_iris.ipynb
