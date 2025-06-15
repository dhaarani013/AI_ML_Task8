# Task 8 - Clustering with K-Means

## 🔍 Objective
Perform unsupervised learning using K-Means clustering to group data into meaningful clusters. Evaluate cluster quality using metrics like the Elbow Method and Silhouette Score.

## 📁 Dataset
**Mall Customer Segmentation Dataset**  
Source: [Kaggle - vjchoudhary7/customer-segmentation-tutorial-in-python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## ⚙️ Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📌 Workflow
1. **Data Loading & Cleaning**
   - Loaded dataset and checked for nulls
   - Selected relevant features for clustering

2. **Data Preprocessing**
   - Scaled features using `StandardScaler`

3. **K-Means Clustering**
   - Applied KMeans with different `k` values
   - Used **Elbow Method** to identify optimal `k`

4. **Evaluation**
   - Calculated **Silhouette Score** for cluster validity

5. **Visualization**
   - PCA used for 2D projection of clusters
   - Scatter plot with color-coded clusters

## 💡 Concepts Practiced
- K-Means algorithm and clustering logic
- How to choose optimal `k` (Elbow method)
- Interpreting Silhouette Score
- Visualizing high-dimensional data using PCA
