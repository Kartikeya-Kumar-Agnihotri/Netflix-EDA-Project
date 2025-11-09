#  Netflix Shows Data Analysis

### 📘 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Netflix dataset to uncover insights about the platform’s movies and TV shows.  
It involves data cleaning, visualization, and interpretation of patterns such as genre trends, release years, and country-wise content distribution.

---

###  Dataset
**File:** `netflix_titles.csv`  
**Source:** [Kaggle - Netflix Movies and TV Shows Dataset](https://www.kaggle.com/shivamb/netflix-shows)

**Columns:**
- show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

---

### 🧩 Steps in the Project
1. **Data Loading & Inspection**  
2. **Handling Missing Values**  
3. **Data Cleaning and Preparation**  
4. **Visual Analysis using Matplotlib**  
   - Movies vs TV Shows  
   - Titles Added Over the Years  
   - Top 10 Countries Producing Content  
   - Ratings Distribution  
   - Duration Distribution  
   - Genre Analysis (Bar/Pie Charts)
5. **Insights & Conclusions**

---

### 🧠 Key Findings
- Majority of Netflix content are **Movies (≈70%)**.  
- **United States, India, and UK** dominate content production.  
- Sharp increase in titles after **2015**, peaking around **2019–2020**.  
- **TV-MA** and **TV-14** are the most frequent ratings.  
- **International Movies**, **Dramas**, and **Comedies** are top genres.

---

### 🛠️ Technologies Used
- **Language:** Python  
- **Libraries:** Pandas, Matplotlib  
- **Environment:** Jupyter Notebook  

---

### 📁 Files in Repository
| File | Description |
|------|-------------|
| `Netflix_EDA.ipynb` | Jupyter notebook containing all analysis code |
| `netflix_titles.csv` | Dataset used for analysis |
| `TOPIC – Data Analysis on Netflix Shows.pptx` | Project presentation |
| `requirements.txt` | List of dependencies for running the notebook |

---

### 📸 Visuals
Include a few chart images (e.g., Movies vs TV Shows, Country-wise Pie Chart).

---

### 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
