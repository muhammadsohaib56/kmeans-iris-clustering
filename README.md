# 🌸 K-Means Clustering on Iris Dataset


````markdown
This project applies **K-Means Clustering**, an unsupervised learning algorithm, to the famous **Iris flower dataset**. The model attempts to group the flowers into clusters based on their sepal and petal measurements — without using the actual species labels.

---

## 📊 Dataset

The Iris dataset contains 150 samples with the following features:
- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`

Although each sample belongs to one of three species (`setosa`, `versicolor`, `virginica`), clustering is performed without using this label.

---

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---
````
## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/kmeans-iris-clustering.git
   cd kmeans-iris-clustering
   ```
2. Launch the notebook:

   ```bash
   jupyter notebook Applying-KMeans-iris-dataset.ipynb
   ```

---

## 🧠 Techniques Used

* **KMeans** from `sklearn.cluster`
* **Elbow Method** to determine optimal `K`
* **Data visualization** with scatter plots and color-coded clusters
* Optional: PCA to reduce dimensions for visualization
* Comparison with actual species labels (for evaluation only)

---

## 📈 Output & Results

* Cluster visualizations in 2D (e.g., petal length vs width)
* Elbow graph showing best number of clusters
* Accuracy comparison using confusion matrix or clustering score (optional)

---

## ✅ Conclusion

* Successfully groups flowers into clusters without labels
* Great demonstration of unsupervised learning using a simple and well-known dataset

---

## 📂 File Structure

```
kmeans-iris-clustering/
│
├── Applying-KMeans-iris-dataset.ipynb    # Main notebook
├── README.md                             # Project overview
```

---

## 🤝 Contributing

Feel free to contribute:

* Try other clustering techniques like DBSCAN
* Visualize with PCA or t-SNE
* Add clustering metrics like silhouette score

---

## 📜 License

[MIT License](LICENSE)

---

