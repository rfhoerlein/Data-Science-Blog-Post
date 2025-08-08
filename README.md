# Developer Salary Analysis and Prediction

## Project Motivation

This project analyzes the Stack Overflow Developer Survey dataset to identify which combinations of skills, technologies, and experience levels are most strongly associated with high-salary developer roles in the United States. By leveraging machine learning, specifically a Random Forest Regressor with hyperparameter tuning, the goal is to build a predictive model for developer salaries and interpret feature importances to derive actionable insights for professionals and recruiters.

---

## Libraries Used

- `pandas` — for data manipulation and cleaning  
- `numpy` — for numerical operations  
- `matplotlib` and `textwrap` — for data visualization and formatting labels  
- `scikit-learn` — for machine learning modeling, including train/test split, Random Forest, hyperparameter search (RandomizedSearchCV), and evaluation metrics  
- Other standard Python libraries as needed  

---

## Repository Files and Description

- `Data Cleaning and Modeling.ipyb` — a Jupyter notebook containing all data cleaning, filtering, feature engineering, model training, hyperparameter tuning, evaluation, and visualization code. This is the primary script driving the entire analysis.
- **Developer Survey/** — a folder containing the raw survey dataset files, including the CSV data, the survey schema, and any related documentation PDFs necessary to understand the data structure and questions.
- `README.md` — this file, summarizing the project, libraries, files, results, and acknowledgments 


---

## Summary of Results

- After rigorous filtering and cleaning of the survey data, a Random Forest Regressor was trained to predict developer salaries.  
- The model’s best hyperparameters were identified via RandomizedSearchCV, improving predictive performance.  
- Evaluation metrics such as Mean Absolute Error (MAE) and R² score were used to assess model accuracy.  
- Feature importance analysis revealed which skills, technologies, and experience attributes most influence salary, helping answer the core business question:  
  **“What combination of skills, technologies, and experience levels are most strongly associated with high-salary developer roles in the US?”**  
- Visualizations highlight the top factors within each category, offering actionable insights for developers aiming to maximize their salary potential.  
- A blog post summarizing the results can be found here: https://medium.com/@rfhoerlein/what-drives-developer-salaries-bdd6288629f6

---

## Acknowledgements

- This project was completed independently using official pandas documentation for data manipulation guidance.  
- I also utilized AI coding assistants, including ChatGPT, to help with code formatting, debugging, and improving code structure.   
- Special thanks to the Stack Overflow Developer Survey team for providing the dataset used in this analysis.

---

If you have any questions or feedback, feel free to reach out!
