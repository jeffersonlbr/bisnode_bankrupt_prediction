## Project context
Building a complete data preprocessing and predictive classification model pipeline aimed at forecasting whether a company will cease operations within the next two years. The data was collected and curated by Bisnode, a European company specializing in business information. The dataset spans from 2005 to 2016 and encompasses companies across various sectors of the economy (such as electronics, electrical equipment, engines, etc.) and services (food, beverages, and lodging). Companies with revenue exceeding 100 million Euros were anonymized to minimize identification possibilities.

## Preprocessing Activities (Python, R)
The entire data preprocessing pipeline was carried out in Python. Python scripts were used for data preprocessing, modeling, and exploratory analysis. For the final delivery of the predictive models, R Markdown was employed.

## Information
- Remove records from the year `2016` from your data.
- Created a column for the dependent variable that will be the target of prediction.
- A company has ceased operations if it was active in year X but did not report any sales in year X + 2.
- Filtered data from the year `2012`.
- Check for inconsistencies (null values, blank values, mean, median, mode, NaN values, negative numbers).
- `np.where` was used for adjustements, so that where Sales < 0, replace with 0.
- If this variable is highly skewed, is it worth creating new columns that represent the log value of this column?
- The company age was created using feature engineering (`founded_year` - `year`).
- Data was filtered to include companies with revenue below 10 million euros and above 1000 euros.

## Final model
- Jupyter Notebook and VS Code were used, containing all the modeling code.
- Markdown was used to explain ideas, code, graphs, etc.
- Descriptive statistics and graphs were employed.
- Files are available in the formats: .ipynb and .html.

## ML model objective
The objective of this project is to develop a predictive model to indicate whether a company will cease operations within a period of up to two years. 

- 
- The predictive models used was: decision trees, random forests, and ROC curve analysis.
- Hyperparameter tuning was also performed.
- The models were compared in terms of their predictive performance.
