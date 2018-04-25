Logistic Regression on Titanic and Low Birth Weight Data
----------------

This project involves using Spark to create predictive models for analyzing two datasets: a Titanic survivors dataset, and a low birth weight infants dataset.  The first part of the analysis involves using logistic regression and Naive Bayes to categorize Titanic victims based on whether they survived.  The second part of the analysis involves using logistic regression, Naive Bayes, and decision trees to predict whether babies will be born with low birth weight.  In this part, I will evaluate each model's performance to determine which technique is most effective for this dataset.

The full report can be found in the file "Spark Regression.pdf".  This report includes two parts: part 1 involves analyzing the Titanic data, and part 2 involves analyzing low birth weight data.  The report shows a complete breakdown of my analysis, including problem identification, motivation, data exploration, data partition, model implementation, model results, model comparison, and proposed solutions.  Tables and visualizations are included in the main body of my report.

The datasets "Titanic.csv" and "lowbwt.csv" were provided by my course instructor at the University of Maryland University College.

Three Python notebooks were created in this assignment.  Part 1 uses two notebooks: "machineLearningTitanic.ipynb" for logistic regression and "machineLearningTitanicNB.ipynb" for Naive Bayes.  Part 2 uses the notebook "machineLearningLowBirthWeight.ipynb," which contains all three methods used in the analysis.  The requirements are described in the file "requirements.txt".  I used IBM Watson Spark service for this project.  To create the program, you can import the notebooks into the IBM Spark service and load the .csv files as data assets.

The notebook results have been attached as HTML files, and they can be accessed without loading the files into Spark.  "Titanic_LogisticRegression.html" and "Titanic_NaiveBayes.html" include the results for the first part, and "LowBirthWeight_Models.html" contains the results for the second part.