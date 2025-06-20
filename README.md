:

🎬 Netflix Movies and TV Shows Clustering
A machine learning project to cluster Netflix content using unsupervised learning techniques. The project focuses on understanding content similarities based on features like genre, rating, duration, and release year, aiming to enhance content understanding and recommendation strategies.

📌 Objective
To group Netflix Movies and TV Shows into meaningful clusters using unsupervised learning methods such as K-Means, Hierarchical Clustering, and DBSCAN. This helps identify content patterns and support better decision-making for recommendations and content planning.

📁 Dataset Details
Source: Netflix Movies and TV Shows dataset (Kaggle)

Records: 7,787 entries

Features Used:

Type (Movie / TV Show)

Duration (converted to integer for analysis)

Genres (multi-valued, one-hot encoded)

Age rating / Maturity rating (converted to numeric categories)

Release Year (as numerical feature)

Content Age (derived as current year - release year)

🧰 Tools & Libraries
Language: Python

Libraries:

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Visualization

Scikit-learn – Clustering models & preprocessing

Scipy – Hierarchical clustering (linkage, dendrogram)

t-SNE / PCA – Dimensionality reduction for visualization

🔄 Workflow
1. Data Preprocessing
Cleaned missing/null values

Converted Duration to numerical values

Created Content Age feature

One-hot encoded multi-category columns like Genres

Standardized features using StandardScaler

2. EDA (Exploratory Data Analysis)
Movies vs TV Shows count

Distribution of content over years

Genre-wise content count

Duration patterns across content types

3. Feature Engineering
Extracted numeric and categorical features

Created a structured matrix for clustering input

4. Clustering Algorithms Applied
✅ K-Means Clustering

Used Elbow Method & Silhouette Score to determine optimal k

Final clusters formed and analyzed

✅ Hierarchical Clustering

Generated dendrogram to visualize cluster separation

Explored different linkage methods (ward, average)

✅ DBSCAN

Detected noise and core samples

Worked well on dense regions of similar content

5. Visualization
Plotted cluster separation using PCA / t-SNE

Cluster profiles with genre/duration/rating patterns

📈 Results
Optimal K for K-Means: 4 clusters (based on Elbow + Silhouette)

Cluster insights:

Cluster 0: Recent TV Shows with short duration

Cluster 1: Older content with longer runtime

Cluster 2: Mixed genres with mid-range content age

Cluster 3: Dominated by family & drama genres

DBSCAN identified sparse outliers and niche content

✅ Conclusion
Clustering revealed useful groupings in Netflix content:

Helps improve content discovery

Supports better recommendation models

Offers insights for content curation

🔮 Future Enhancements
Add user ratings & watch time data for behavior-based clustering

Integrate NLP on content descriptions for deeper clustering

Build recommendation system using cluster proximity

🙋‍♀️ Author
Bhuvaneshwari B
Freelance Data Analyst | Python | SQL | Machine Learning
📍 Bangalore, India
📧 bhuvi.bhuvana15@gmail.com
https://github.com/BhuvanaB34

