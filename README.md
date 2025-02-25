# Bird_Classification_Project
A course project for practicing exploratory data analysis and ensemble machine learning techniques.

### Exploratory Data Analysis
The data was loaded and inspected for missing or bad entries. Content and shape of the data was discussed in detail.

### Data Transformation
Transformed data from long to wide format using pivot method to handle duplicate rows due to how imgid and attid interact. imgatt and imglabels were merged to sync indexes before splitting and shuffling for training and testing sets.

### Machine Learning Models
A random forest classifier was initialzed, trained, and made predictions to compare performances with a KNN classifier and decision tree classifer using training/testing accuracies and Kfold cross validation.

### Hyperparamter Tuning
Grid search was used to find the optimal hyperparamters of various algorithms and a stacking ensemble was created from algorithms with optimized hyperparameters. The final challenge of the assignment was improving the ensemble performance using any techniques neccesary, which was further discussed in the notebook.
