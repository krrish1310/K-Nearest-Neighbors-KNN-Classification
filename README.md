# Task 6: K-Nearest Neighbors (KNN) Classification

## 📌 Objective
To understand and implement the K-Nearest Neighbors (KNN) algorithm for multi-class classification using the Iris dataset.

## 📊 Dataset
**Iris Dataset**: Contains measurements of 150 iris flowers from 3 different species.

- Features: Sepal Length, Sepal Width, Petal Length, Petal Width
- Target: Species (Setosa, Versicolor, Virginica)

## 🛠 Tools Used
- Python
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

## 🚀 Steps Performed
1. Loaded and explored the dataset.
2. Preprocessed data:
   - Removed `Id` column.
   - Encoded the `Species` column.
   - Normalized features using `StandardScaler`.
3. Split the data into training and testing sets.
4. Implemented KNN using `sklearn.neighbors.KNeighborsClassifier`.
5. Evaluated model using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
6. Experimented with different `K` values (1–20) and plotted accuracy vs K.
7. Visualized decision boundaries using the first two features.

## 📈 Result
- Best Accuracy Achieved: ~96-100% (depending on K)
- Optimal `K` value: Found using accuracy graph.

## 📂 Files
- `knn_iris.ipynb`: Jupyter Notebook with all code and plots.
- `Iris.csv`: Dataset used.

## 🔗 Submission
Submit your GitHub repository link [here](https://forms.gle/8Gm83s53KbyXs3Ne9).
