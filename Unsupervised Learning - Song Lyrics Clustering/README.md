# Song Lyrics Clustering — Unsupervised Learning

_Intro to Artificial Intelligence — University of Tehran_

This project applies **unsupervised learning** techniques to cluster English song lyrics into meaningful groups.  
The task involves **text preprocessing, feature extraction, clustering, and evaluation**, with comparisons across multiple algorithms and dimensionality reduction for visualization.


## Tasks

1. **Data Preprocessing & Feature Extraction**
   - Clean and normalize text:  
     - Remove stop words  
     - Apply stemming or lemmatization  
     - Remove punctuation and irrelevant characters
   - Justify preprocessing choices in terms of clustering performance.
   - Use **SentenceTransformers** with the `all-MiniLM-L6-v2` model to generate feature vectors.

2. **Clustering Methods**
   - Apply and compare:
     - **K-Means** (with `elbow method` for choosing K)  
     - **DBSCAN**  
     - **Hierarchical Clustering**
   - Analyze differences between **supervised vs. unsupervised** approaches.
   - Evaluate clustering quality using both **visual inspection** and **quantitative metrics**.

3. **Dimensionality Reduction & Visualization**
   - Use **PCA** to reduce feature dimensions to 2D or 3D.  
   - Visualize clusters and compare results across algorithms.
   - Inspect and interpret **clustered lyrics samples** for semantic and topical similarity.

4. **Evaluation & Analysis**
   - Compute clustering performance metrics:
     - **Silhouette Score**
     - **Homogeneity Score**
   - Compare the results of different methods, highlight strengths and weaknesses.
   - Print two representative samples per cluster for semantic analysis.
   - Select the best-performing clustering method and justify the choice.


## License

This project is licensed under the **MIT License**.


## Acknowledgements

Developed under the supervision of **Dr. Fadaei** and **Dr. Yaghoubzadeh**  
Designed by **Amirhossein Arefzadeh, Mobina Mehrazar, Amirali Rahimi**

