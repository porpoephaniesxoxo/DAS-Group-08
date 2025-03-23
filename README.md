# Group 8: An Analysis of Factors Influencing High IMDB Ratings
## Our objective is To determine which factors of films are associated with an IMDB rating above 7 by using a Generalised Linear Model (GLM).

## Data description
- **Source**: IMDB film database 
- **Observations**: 2,847 films
- **Variables**:
  - `film_id`: Unique identifier
  - `year`: Year of release
  - `length`: Duration (minutes)
  - `budget`: Production budget (in $10 million)
  - `votes`: Number of viewer votes
  - `genre`: Genre of the film
  - `rating`: IMDB score from 0–10

## Tools 
- Rstudio with Quarto

## Methodology
- Data Cleaning:
  - Removed missing values
  - Converted categorical variables
  - Created binary variable `rating_above_7`
  - Grouped `year` into `decade_group`
- Exploratory Data Analysis (EDA):
  - Summary statistics for numeric and categorical variables
  - Target Variable Exploration
  - Distribution plots and bivariate relationships
  - Correlation Matrix
- Modeling:
  - Logistic regression using GLM
  - Compared models using AIC
  - Applied stepwise selection and variable reduction
- Model Diagnostics:
  - Residual analysis, ROC & AUC (0.95), confusion matrix (Accuracy = 88%)
  - Multicollinearity check (VIF < 2)

## Files in this repository
- Group_08_Analysis.qmd
- `dataset08.csv`
- README.md

## Contributors
- Pantita Kaewdee (cleaning & EDA)
- Yukun Zhang (model building & diagnostics)
- Danni Zhang (Slide design & presentation)
- Junxi Zhang (Slide design & presentation)
- Chenyang Hu (Slide design & presentation)

