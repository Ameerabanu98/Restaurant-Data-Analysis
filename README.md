# Restaurant-Data-Analysis

This project analyzes a dataset of over 9,500 restaurants, focusing on trends in customer ratings, votes, cuisine types, and pricing. The project includes visual exploration and a basic regression model to predict restaurant performance using features such as price range and votes. An interactive map of restaurant locations is also provided.

---

## 📌 Objectives

- Explore restaurant trends based on:
  - Cuisines
  - Price range
  - Customer ratings
  - Number of votes
- Visualize restaurant locations on an interactive map
- Build a regression model to predict restaurant ratings

---

## 📊 Dataset Features

The dataset contains the following key columns:

| Column            | Description                                     |
|-------------------|-------------------------------------------------|
| Restaurant Name   | Name of the restaurant                          |
| Cuisines          | Cuisines offered (can include multiple types)   |
| Aggregate rating  | Overall rating of the restaurant (0 to 5)       |
| Votes             | Number of users who rated the restaurant        |
| Price range       | Cost level (1: Low, 4: High)                    |
| Latitude & Longitude | Geographical location of the restaurant     |
| City              | City of the restaurant                           |
|Country Code        | Represents the country of the restaurant        |


     It include many other features such as Address, Locality, Online Delivery , Table booking,etc.
---

## 📍 Visualizations

- **Bar Charts**:
  - Number of restaurants by cuisine
  - Total votes per cuisine
  - Distribution of ratings and price ranges
- **Interactive Map**:
  - Restaurant locations plotted using `plotly.express.scatter_mapbox`
  - Colored by aggregate rating
  - Zoom and pan enabled

---

## 🤖 Regression Model

- A linear regression model was built using **scikit-learn**.
- **Objective**: Predict the restaurant's **aggregate rating** based on features like:
  - Number of votes
  - Price range
  - Services offered by restaurants.4
- **Steps Involved**:
  - Data cleaning and encoding
  - Feature selection and scaling
  - Model training and evaluation
- **Evaluation**: Model performance was evaluated using R² score and RMSE.

---

## 🛠️ Tools & Technologies Used

- Python 3
- Google Colab
- pandas, numpy
- matplotlib, seaborn
- plotly.express
- scikit-learn (for regression model)

---

## 🧾 How to Run the Project

1. Open the notebook in Google Colab
2. Upload the dataset (`restaurant_data.csv`) when prompted
3. Run each code cell to:
   - Perform data analysis
   - Generate visualizations
   - Train and evaluate the regression model

---

## 📁 Files Included

- `restaurant_analysis.ipynb` – Main notebook with code and visuals
- `dataset.csv` – Dataset file (uploaded manually in Colab)
- `README.md` – Project overview

---

## 🙋‍♂️ Author

**Ameera Banu**  
Data Analyst & Visualization Enthusiast




