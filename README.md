# Olympic Medal Prediction ML

## Project Overview
This project predicts the number of medals a country can win in future Olympic Games using Machine Learning techniques and historical Olympic data.

## Dataset Features
The model uses the following features:

- Number of Athletes
- Average Age of Athletes
- Previous Olympic Medal Count
- Historical Olympic Performance

## Dataset

Features:
- team
- country
- year
- athletes
- age
- prev_medals
- medals

## Machine Learning Model
- Random Forest Regressor
- Feature Engineering
- Data Preprocessing using Pandas

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

## Model Performance

### Evaluation Metrics

- Mean Absolute Error (MAE): 3.44
- R² Score: 0.89

### Interpretation

- The model explains approximately 89% of the variance in Olympic medal counts.
- On average, predictions differ from actual medal counts by around 3–4 medals.

## Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Prediction
7. Performance Evaluation

## Future Improvements

- Add GDP and population data
- Include host nation advantage
- Add sport-wise athlete information
- Use advanced boosting algorithms such as XGBoost

## Author

Nishi Chauhan

B.Tech Artificial Intelligence & Data Science
