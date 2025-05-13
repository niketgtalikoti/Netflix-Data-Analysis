# 📊 Netflix Content Analysis & Clustering

This project analyzes and segments Netflix's content library using data science techniques, focusing on uncovering trends in content type, genre distribution, regional production, and audience targeting. It also includes unsupervised machine learning via clustering to identify content groupings for strategic recommendations.

---

## 📌 Project Objectives

* Analyze Netflix’s vast content library using EDA techniques
* Identify trends in content type, genre, duration, and country of origin
* Apply TF-IDF and K-Means clustering to segment content by genre
* Use PCA for dimensionality reduction and cluster visualization
* Derive business insights to improve content strategy and personalization

---

## 🧰 Tools & Technologies Used

* **Languages**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn
* **ML Techniques**: TF-IDF, K-Means Clustering, PCA
* **Data**: Netflix Movies & TV Shows Dataset (CSV format)

---

## 📈 Exploratory Data Analysis (EDA)

* **Content Type Split**: Movies dominate the catalog (\~97%), TV Shows are underrepresented
* **Rating Trends**: Majority of content is rated for mature/teen audiences (TV-MA, TV-14, R)
* **Release Trends**: Content surged 2016–2019, with a decline post-2020 (possibly due to COVID-19)
* **Top Countries**: U.S. leads content production, followed by India and other global markets
* **Genre Distribution**: International Movies, Dramas, and Comedies are most prevalent
* **Actor/Director Trends**: Veteran Indian actors are dominant; director data shows diverse international representation
* **Duration Analysis**: Indian films show longer average durations; smaller countries skew high due to fewer entries

---

## 🔍 Clustering Analysis

* **TF-IDF Vectorization** applied to genre tags
* **K-Means Clustering (k=5)** used to group content into 5 genre-based clusters
* **PCA** used for dimensionality reduction and interactive cluster visualization using Plotly
* **Cluster Insights**:

  * Two large clusters represent mainstream genres
  * Smaller clusters represent niche or mixed-genre content

---

## 💡 Key Business Insights

* Netflix has a movie-heavy catalog with regional content dominance by the US and India
* Genre clustering can aid in:

  * Improving personalization & recommendation systems
  * Highlighting over/under-represented genres
  * Informing region-specific content strategies
* Potential growth areas include:

  * Increasing TV show content, especially outside the US
  * Addressing gender imbalance in featured talent
  * Investing in more family-oriented content

---

## 🧠 Conclusion

This project demonstrates how unsupervised learning and visual analytics can be applied to a content-based dataset for strategic business insights. The genre clusters provide a valuable lens into Netflix’s catalog and open avenues for enhanced content curation and user experience optimization.



