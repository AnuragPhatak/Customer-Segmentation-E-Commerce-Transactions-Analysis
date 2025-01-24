# **Project Workflow**
## **1. Data Preprocessing & Feature Engineering**
- Created customer-level aggregated features (**Total Spending, Purchase Count, Unique Products**).
- Encoded categorical variables and scaled numerical features using **MinMaxScaler**.

## **2. Clustering Approach (K-Means)**
- Used **K-Means Clustering** to segment customers into distinct groups.
- Identified the **optimal number of clusters** using the **Elbow Method**.
- Evaluated clustering performance using **Davies-Bouldin Index** and **Silhouette Score**.

## **3. Cluster Visualization**
- **3D PCA Plot** for improved visualization of customer clusters using **Matplotlib** and **Plotly**.

## **4. Business Insights & Recommendations**
- Analyzed **customer spending patterns** and **purchase frequency**.
- Derived **actionable insights** for high-value customers and potential engagement strategies.

---

# **Key Findings**

## **Clustering Insights**
| **Cluster** | **Avg Total Spending** | **Avg Purchase Count** | **Avg Unique Products** |
|------------|----------------------|----------------------|----------------------|
| **0**      | 0.3115               | 0.4255               | 0.4620               |
| **1**      | 0.3483               | 0.4684               | 0.4966               |
| **2**      | 0.3102               | 0.4822               | 0.5261               |
| **3**      | 0.3166               | 0.4404               | 0.4622               |

- **Cluster 1** represents **high-value customers** with the highest spending and purchase count.
- **Cluster 2** has the most **diverse shopping patterns**, with the highest unique product purchases.
- **Clusters 0 and 3** are **moderate shoppers** with steady but lower engagement levels.

---

## **Evaluation Metrics**
- **Davies-Bouldin Index:** **0.609** (Indicates well-separated clusters).
- **Silhouette Score:** **0.639** (Moderate clustering strength).

---

# **Technologies Used**
- **Python** (**pandas, numpy, sklearn, scipy**) – Data preprocessing and clustering.
- **Matplotlib,**Plotly** & Seaborn** – Data visualization.
