CS412 - Machine Learning Project
--------------------------------
Overview
With this project, we aimed to predict the first assignment grades of the CS-412 course by using students' ChatGPT conversation histories.
Atahan Bozkuş - 28471
Emir Ay - 28150
-------------------------------
1) Library Imports
Notebook starts by importing various Python libraries. These libraries include common data analysis and machine learning libraries such as matplotlib, seaborn, pandas, numpy, sklearn. This step ensures that the necessary tools are available for the data analysis and modeling process. In particular, the sklearn library offers various functions for model training and evaluation.
-------------------------------
2) Text Preprocessing
The text preprocessing step is a key component of natural language processing (NLP) applications. The preprocess_text function defined here cleans up text, making it more suitable for machine learning models. The function performs operations such as converting text to lowercase, clearing non-alphanumeric characters, and removing stop words.
-------------------------------
3) Data Extraction and Cleansing Procedures
This section includes extracting and cleaning dialog and code data from HTML files. The extract_and_clean_code function is used to extract and organize the necessary information from the HTML content. This process is critical to make the data ready for analysis.
-------------------------------
4) Clearing Non-ASCII Characters
This step ensures that non-ASCII characters are removed from the text data. This process helps make text data more consistent and suitable for analysis. The clean_text function performs this operation and is applied to the texts.
-------------------------------
5) Data Analysis and Visualization
Later sections of the notebook include data analysis and visualization steps. In these steps, various analyzes are performed on the data sets using matplotlib and seaborn libraries and the results are visualized. These visualizations make it easier to understand data and gain insights.
------------------------------
6) Model Training and Evaluation
In the model training section, machine learning models are trained and evaluated using various functions of the sklearn library. This process includes the steps of separating the data set into training and test sets, training the model, and evaluating its performance. Model evaluation is typically done using error metrics and cross-validation methods.
------------------------------
7) Conclusion and Evaluation
Importing Model Performance Metrics
At the beginning of the notebook, the metrics to be used for model evaluation are imported. In this section, the from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score line makes the Mean Absolute Error (MAE), Mean Squared Error (MSE) and R-Square (R²) metrics ready for use to evaluate the performance of the model. These metrics are standard tools for measuring how accurate the model's predictions are.
Calculating and Displaying R-Square Value
In another code cell, the performance of the model on the test data set is evaluated. Here, the R-Square value was calculated using the r2_score function. R-Square is a metric that shows how much of the variance in the data set the model can explain. A high R-Square value indicates that the model explains the data well. It measures whether the model makes predictions on the test set and how compatible these predictions are with the real values. The resulting R-Square value reflects the overall success of the model and is used as an important indicator when evaluating the performance of the model.
