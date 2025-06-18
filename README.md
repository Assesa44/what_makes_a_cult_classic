# 🎬 What Makes a Cult Classic?  
*A K-Means Clustering Analysis of Films*

![rob-griffin-AnlxRJPYuLI-unsplash](https://github.com/user-attachments/assets/2f0f71f7-5675-4dc9-bf98-4b7ce16a84cd)

## 📌 Project Overview
This project explores whether we can use clustering to group movies into meaningful categories and uncover where cult classics tend to live. By analyzing features like ratings, revenue, genre, and votes, we attempt to identify patterns that set these beloved but often under-the-radar films apart.

---
## 📊 Tools & Techniques
- *Python* (pandas, numpy, seaborn, matplotlib, scikit-learn)
- *K-Means Clustering*
- *Feature Engineering & One-Hot Encoding*
- *Standardization*
- *Exploratory Data Analysis (EDA)*

---
## 🧠 Key Steps

1. *Data Cleaning*  
   - Handled missing values  
   - Selected key features: ratings, votes, revenue, genre

2. *Feature Engineering*  
   - Encoded categorical variables (e.g., genre)  
   - Scaled numerical features for fair clustering

3. *Clustering*  
   - Used K-Means to group movies  
   - Chose the number of clusters using the Elbow Method

4. *Visualization*  
   - Plotted genre vs cluster, revenue vs rating, and more  
   - Interpreted each cluster (e.g., blockbusters, cult hits, niche dramas)

---
## 🔍 Findings

- *Cluster 0*: High-budget blockbusters with massive votes and revenue.
- *Cluster 1*: Underrated films — high IMDB ratings, low revenue.
- *Cluster 2*: Genre-heavy, middle-ground performers (possible cult favorites).

![image](https://github.com/user-attachments/assets/a313d9f1-5fa4-413c-b728-1f029867e187)

These insights suggest that cult classics often lie in clusters with modest earnings but strong audience appreciation.

---
## 💡 Suggestions for Improvement

- Add more features like director, cast popularity, or release date
- Try alternate clustering algorithms (DBSCAN, Agglomerative)

---
## 📁 How to Run This Project

1. *Clone the repository*  
   ```bash
   git clone https://github.com/Assesa44/what_makes_a_cult_classic.git

2. Install dependencies

pip install -r requirements.txt

3. Run the notebook

Open notebook.ipynb in Jupyter or Colab and run all cells.

> Note: The cleaned dataset and all processing steps are included. You don't need any external data downloads.

---
🧑‍💻 Author

Vanessa Sandra
Student of Data Science | Curious about storytelling through data | Fast learner | Open to opportunities 💼

---

⭐ If you like this project...

Feel free to fork it, star the repo, or connect with me on LinkedIn!

*Email* -> veesandra30@gmail.com
