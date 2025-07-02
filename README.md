# Customer-Segmentation

Customer Segmentation using K-Means Clustering

This project aims to segment customers into distinct groups based on their purchasing behavior and numerical attributes such as **Annual Income** and **Spending Score**, using the **K-Means Clustering algorithm**.

Built as an interactive and fully visualized pipeline compatible with **Google Colab**, the solution guides users through every step:

1. Data Upload & Exploration: Uploads a CSV file, explores the dataset, and visualizes feature relationships with heatmaps and statistics.
2. Preprocessing: Handles missing values, scales features, and filters relevant numerical columns while excluding identifiers like CustomerID.
3. Optimal Cluster Selection: Determines the ideal number of clusters using both the **Elbow Method** and **Silhouette Score**, with interactive user input for customization.
4. K-Means Clustering: Applies KMeans to segment customers and evaluates clustering quality using silhouette metrics.
5. Visualization: Includes **2D and 3D scatter plots**, **centroid visualization**, and **cluster-wise feature distribution**, helping users understand how each group behaves.
6. Business Insight Generation: Interprets clusters in human-readable terms (e.g., High Income – Low Spending), supporting strategic marketing and customer targeting.
7. Result Export: Outputs labeled data with cluster assignments as a downloadable CSV file for further use.

📊 **Tools & Libraries Used**:

* Python, Pandas, NumPy
* Scikit-learn for ML
* Matplotlib & Seaborn for visualizations
* Google Colab for deployment & file upload

---

### 🔍 Key Outcome:

* Automatically discovers meaningful **customer segments**
* Helps businesses tailor **marketing strategies**, improve **customer retention**, and **increase ROI**

