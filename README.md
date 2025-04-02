# Machine Learning Regression Project: Predicting Continuous Values

### Introduction
**Overview:** This project was undertaken as part of my graduate diploma studies for the university course titled 'Foundations of Computer Science - Python B'. I was tasked with identifying a data source to work with and building a machine learning pipeline to answer questions that I establish. Through this project, I was able to demonstrate my skills in Python, and apply my understanding of regression problems to solve a real-life problem. 

**Purpose:** The real-world problem I addressed involved analysing flight booking data to develop a model capable of accurately predicting future flight prices for consumers. 

**Dataset:** The dataset I sourced comprised booking data from India's top six metropolitan cities. It contained 200,000 entries and included a mix of dates, numerical values, and textual strings. 

### Methodology
**Pipeline Overview:** Data pre-processing steps for this analysis involved applying scaling features, data transformations, and feature engineering to extract meaningful information. Four regression models were used; Support Vector Machine Regression, Polynomial Regression, Random Forest Regression, and a Neural Network. For each of these models the optimal parameter values were used to fit the model. 

**Tools and libraries**: The following Python libraries and tools were used in this analysis:
- pandas
- NumPy
- matplotlib
- seaborn
- math
- scikit-learn
- joblib

### Results
**Model Performance**: All models RMSE was compared to that of a naive baseline, to determine which model was performing the best. All models RMSE was lower than that of the baseline, indicating that all models had predictive power. The Random FOrest Regression model was found to have the highest accuracy. This could be due to its flexibility in handling non-linear relationships giving it an advantage over the other models, and its ensemble method of prediction ensuring it is more robust to outliers. 

### Challenges and Learnings
**Challenges**: A challenge I faced in this analysis was the lengthy amount of time it was taking to execute certain methods, particularly when tuning the model hyperparameters. To solve this, I initiated a PCA into the pipeline to reduce the dimensionality and complexity of the data. I also used the Intel(R) Extension for Scikit-learn, which greatly accelerate the scikit-learn code. Another matter was choosing appropriate models for this analysis. I had to pick regression models that would perform well on the specific dataset that was being used. 

**Learning Outcomes:** This analysis was a great opportunity to apply the skills I had already gained to a real-world problem. Through my studies at University, it is easy to become accustomed to using datasets that are provided by my educators, which are often clean and easy to handle. This can be followed by instructions on how to proceed with the analysis. In contrast, this task required considerable independent logical and analytical self-sufficiency. I enjoyed this opportunity to learn how to navigate and tailor the machine learning process to a specific situation, and to infer for myself the conclusions that can be gained from the analysis results. 

### How to Run the Code
You can view the notebook directly in GitHub or execute the cells in Jupyter Notebook to explore the analysis.
If you are wanting to view it in GitHub directly, open the file called 'Python Regression Project'. 
If you are wanting to execute the cells in Jupyter Notebook, follow the below steps

1. Download the Jupyter Notebook file directly from this repository. It is title 'Python Regression Project'.
2. This notebook relies on a dataset, called 'economy.csv'. Download the dataset from this repository and ensure the file is placed in the same directory or the appropriate path specified in the notebook.
3. Ensure you have Jupyter Notebook installed.
4. Launch Jupyter Notebook from your terminal
5. Navigate to the directory containing the download notebook file and open it
You can now explore the analysis. 
