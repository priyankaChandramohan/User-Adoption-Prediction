# User-Adoption-Prediction
This project aims to identify factors that predict future user adoption for a product based on user engagement data. The dataset consists of two CSV files: takehome_users.csv containing user information and takehome_user_engagement.csv containing user engagement data. The goal is to define an "adopted user" as a user who has logged into the product on three separate days in at least one seven-day period and identify the factors that influence user adoption.

## Methodology
The project follows the following methodology:
- Data Loading: The dataset files takehome_users.csv and takehome_user_engagement.csv are loaded into pandas DataFrames to work with.

- Data Exploration: The user information and engagement data are explored to understand the dataset's structure, identify missing values, and gain insights into the user behavior and characteristics.

- Feature Engineering: The user engagement data is processed to identify "adopted users" based on the defined criteria of logging in on three separate days within a seven-day period. Additional features are derived from the existing data to capture potential predictors of user adoption.

- Data Preprocessing: The user information and engineered features are preprocessed, including handling missing values, encoding categorical variables, and scaling numerical features.

## Conclusion
This project aimed to identify factors that predict future user adoption based on user engagement data. By analyzing the provided dataset, performing feature engineering, and building a predictive model, we gained insights into the factors influencing user adoption. The project's findings, along with the summary tables, graphs, code, and queries, are documented in the Solution.ipynb Jupyter notebook and you can find the task in the Task Question.pdf.

For any further assistance or inquiries, please reach out to me.
