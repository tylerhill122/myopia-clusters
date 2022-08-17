# myopia-clusters
Applying unsupervised machine learning to fit data to a model and using clustering algorithms to place data into groups. Then, create a visualization that shares the findings.

## Background

You are on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might be distinct groups of patients that would be better to analyze separately. So, your supervisor has asked you to explore this possibility by using unsupervised learning.

You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualization to share your findings with your team and other key stakeholders.

### Part 1: Prepare the Data
1.) Read 'myopia.csv' into a Pandas DataFrame.
2.) Remove "MYOPIC" column from dataset.
3.) Standardize dataset so that columns with larger values do not influence the outcome more than columns with smaller values.

### Part 2: Apply Dimensionality Reduction

1.) Perform dimensionality reduction with PCA.

2.) Further reduce the dataset dimensions with t-SNE and visually inspect the results. Run t-SNE on the principal components (output of PCA transformation).

3.) Create scatter plot of t-SNE output.

### Part 3: Perform a Cluster Analysis with K-means

1.) Create an elbow plot to identify the best number of clusters. Make sure to do the following:

* Use a for loop to determine the inertia for each 'k' between 1 through 10.

* If possible, determine where the elbow of the plot is, and at which value of `k` it appears.

### Part 4: Make a Recommendation

Based on your findings, write up a brief (one or two sentence) recommendation for your supervisor in your Jupyter Notebook. Can the patients be clustered? If so, into how many clusters?