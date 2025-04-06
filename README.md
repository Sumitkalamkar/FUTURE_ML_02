🎬 Movie Box Office Revenue Prediction  
This project was developed as part of an internship task at **Future Interns**. It focuses on predicting the box office revenue of movies using various features from the TMDB dataset, including genre, cast, and production budget, by applying regression techniques.

📁 Dataset  
The dataset used is the TMDB Movie Dataset, which includes metadata such as genres, cast, production companies, budget, revenue, and more.

🎯 Objective  
To build a regression model that predicts the box office revenue of a movie based on its metadata features.

📊 Features Used  
Selected and engineered features such as:
- Genre (one-hot encoded)
- Cast (top actors extracted)
- Budget (log-transformed)
- Popularity
- Runtime
- Production Companies (top companies filtered)

🧠 Model Overview  
Algorithm: Linear Regression & Random Forest Regressor  
Preprocessing:
- Handling missing values
- Feature engineering (categorical encoding, log transformation)
- Train-test split
Evaluation Metrics:
- R² Score
- Root Mean Squared Error (RMSE)
- Residual Analysis

🛠️ Installation  
Install all necessary libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

🚀 How to Run the Project

Place task 2.ipynb and the TMDB dataset CSV file in the same directory.

Open task 2.ipynb in Jupyter Notebook.

Run all cells sequentially to preprocess data, train models, and evaluate performance.

📈 Output Includes

Model accuracy (R² Score)

RMSE value

Key influencing factors (via feature importance)

Visualizations of predicted vs actual revenue

👨‍💻 Author
Sumit — developed as an internship project for Future Interns
