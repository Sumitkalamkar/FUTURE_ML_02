# 🎬 Movie Box Office Revenue Prediction

This project predicts the box office revenue of movies based on various features like **genre**, **cast**, and **production budget** using the TMDB dataset.

## 📌 Objective

To build a regression model that can predict the **box office performance** of movies. This helps in understanding which features contribute the most to a movie’s financial success.

---

## 🧰 Tools & Technologies Used

- **Python**
- **Pandas** & **NumPy** for data manipulation
- **Matplotlib** for data visualization
- **Scikit-learn** for machine learning and model evaluation

---

## 📂 Dataset

- **Source**: The Movie Database (TMDB)
- **Contains**: 
  - Movie title, genre, cast, budget, revenue, and other metadata.
  - Used for supervised regression tasks.

---

## 🔍 Project Structure

- **task 2.ipynb**: Jupyter notebook with the complete code for data preprocessing, model building, and evaluation.
- **README.md**: Project documentation.

---

## 🧪 Workflow

1. **Data Cleaning**: Handle missing values, incorrect formats, and outliers.
2. **Feature Engineering**: 
   - One-hot encoding for genres
   - Top cast extraction
   - Log transformation of budget and revenue
3. **Modeling**:
   - Linear Regression
   - Random Forest Regressor
   - Performance measured using RMSE and R² score
4. **Analysis**: Key factors influencing box office revenue are highlighted.

---

## 📈 Results

- The best-performing model achieved an **R² score of `X.XX`** and **RMSE of `XXXXXXX`**.
- **Key influential factors**:
  - Production Budget
  - Popularity
  - Top Cast Members
  - Genre Categories

> *Insight:* Higher budgets and well-known casts generally correlate with higher box office performance.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/movie-boxoffice-prediction.git
   cd movie-boxoffice-prediction
