# 📚 Book Recommendation System

A **content-based machine learning** project that suggests books similar to the one you input. Simply provide a book title, and the system returns personalized recommendations based on book characteristics.

---

## 🔍 Project Overview

This project uses **KDTree** for efficient nearest-neighbor searches to find books with similar attributes. Recommendations are based on metadata such as:

- Average rating  
- Ratings count  
- Number of pages  

The goal is to provide meaningful book suggestions using **content-based filtering** rather than user behavior.

---

## ✨ Features

- **Personalized Recommendations:** Enter any book title and receive **2 similar book suggestions**
- **Content-Based Filtering:** Compares book metadata—not user history
- **Smart Search:** Handles partial matches and multiple results
- **Rich Dataset:** Based on a GoodReads dataset containing **13,631 books**

---

## 📦 Dataset

This project uses the **GoodReads Books Dataset** from Kaggle, including:

- Titles & authors  
- Average ratings and rating counts  
- Number of pages  
- Language information  
- Publication years (added via web scraping)

---

## ⚙️ Installation

```bash
pip install pandas numpy matplotlib seaborn requests beautifulsoup4 scikit-learn jupyterthemes
```

## ▶️ Usage

**Run the recommendation function**
```recommendation("Harry Potter")```

The system will:
1. Search for matching titles
2. Prompt you to select the correct book if needed
# 3. Return 2 recommended books

```
OUR RECOMMENDATIONS ARE:
FIRST  - Twilight (Twilight #1)
SECOND - The Hobbit or There and Back Again
```

## 👤 Author
Lucas Gustavo Alves