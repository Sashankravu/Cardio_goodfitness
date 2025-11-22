🏋️ CardioGoodFitness Project


📌 Overview This project analyzes customer demographics and treadmill purchase behavior using the CardioGoodFitness dataset. I performed exploratory data analysis (EDA), feature engineering, and statistical comparisons to uncover customer segments and product preferences. The analysis highlights how demographics (age, gender, marital status, income, education) influence treadmill choice (TM195, TM498, TM798).

⚙️ Workflow

Data Preparation – Cleaned dataset, handled categorical variables (Gender, Marital Status, Product).

Descriptive Statistics – Summarized Age, Income, Fitness, Usage, and Miles across products.

Feature Engineering – Created pivot tables and aggregated features (average income, miles, strike rate-like usage metrics).

Visualization – Built histograms, bar plots, and pair plots to reveal customer trends.

Segmentation Analysis – Compared product preferences by gender, marital status, and income groups.

Insights Generation – Derived marketing recommendations based on customer profiles.

📊 Results

Product	Customer Profile	Key Insights
TM195	Younger, entry-level customers with moderate income	Budget-friendly treadmill for beginners
TM498	Balanced demographics, mid-range	Appeals to average-income customers
TM798	High-income, fitness-focused customers	Premium treadmill for enthusiasts
👉 Final Insight: TM195 should be marketed toward budget-conscious beginners, while TM798 appeals to premium fitness enthusiasts.

🚀 Key Learnings

Pivot tables and group-by operations are powerful for customer segmentation.

Visualization storytelling (pair plots, bar charts) makes demographic insights clear.

Income and usage patterns strongly influence product preference.

Documenting findings in a structured notebook and README improves professional presentation.

📂 Project Structure

notebooks/CardioGoodFitness.ipynb → Main notebook with code and analysis.

data/ → Dataset (not included here, add your source).

README.md → Project documentation.

🛠️ Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Statsmodels / Scipy

Jupyter Notebook

📌 Conclusion The analysis revealed clear customer segments for each treadmill model.

TM195: Entry-level, budget-conscious customers.

TM498: Balanced product for average demographics.

TM798: Premium product for high-income, fitness-driven customers.

Future improvements could include predictive modeling (classification of product choice) and deployment of an interactive dashboard using Gradio/Streamlit.

📜 Author Sashank – Data Science & Machine Learning Enthusiast
