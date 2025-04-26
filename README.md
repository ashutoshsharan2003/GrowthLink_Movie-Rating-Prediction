# 🎥 Movie Rating Prediction

This repository contains a machine learning project that predicts IMDb movie ratings based on attributes like genre, director, and other engineered features. The dataset used is specific to Indian movies.

---

## 📖 Task Objectives

- Predict movie ratings using metadata from an IMDb-style dataset.
- Handle missing values and encode categorical features.
- Engineer meaningful features such as:
  - Director success rate (average rating of a director's past movies)
  - Average rating of similar movies based on genre
- Evaluate model performance using standard regression metrics.

---

## 🔄 Steps to Run the Project

### 1. Clone the Repository
```bash
https://github.com/ashutoshsharan2003/GrowthLink_Movie-Rating-Prediction/tree/main
```

### 2. Install Dependencies
If running locally:
```bash
pip install -r requirements.txt
```

Or open the notebook directly on Google Colab.

### 3. Open and Run the Notebook
- Open `movie_rating_model.ipynb`
- Upload the dataset `IMDb_Movies_India.csv` when prompted
- Execute all cells

---

## 🎯 Model and Features

### Features Used:
- Encoded Genre
- Encoded Director
- Director Success Rate
- Average Genre Rating
- (Dummy Budget)

### Model:
- **Random Forest Regressor** from `scikit-learn`
- Trained on an 80/20 train-test split

### Evaluation:
- Mean Squared Error (MSE)
- R² Score

---

## 🌟 Evaluation Criteria

### Functionality
- Accurately predicts movie ratings based on multiple factors

### Code Quality
- Clean, modular code
- Clearly commented and structured

### Innovation & Creativity
- Director-based and genre-based success rates used as creative engineered features

### Documentation
- Complete project explanation in this README
- Easy-to-run notebook for experimentation

---

## 📁 Repository Structure
```
movie-rating-prediction/
|
├── movie_rating_model.ipynb    # Main notebook
├── IMDb_Movies_India.csv       # Dataset
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## 🚀 Future Improvements
- Use actual budget if available
- Include cast-based features (actor popularity)
- Add model comparison (Linear Regression, XGBoost)
- Deploy model as API or web app

---

## ✉️ Contact
For questions or suggestions, please feel free to reach me.
Ashutosh Sharan
ashutoshshsharan22@gmail.com


