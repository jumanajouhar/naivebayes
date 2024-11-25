# Naive Bayes on the IRIS Dataset

### Problem Statement: 
To develop a classification model that can accurately predict the species of an iris flower 
based on four key features: sepal length, sepal width, petal length, and petal width. This task 
involves implementing a Gaussian Naive Bayes classifier and evaluating its performance on 
the IRIS dataset. The project aims to:   
1. Train the model on a subset of the data.   
2. Test it on unseen data to evaluate its predictive capabilities.   
3. Assess the model’s performance using metrics such as accuracy, confusion matrix, and 
classification report. 
### About the IRIS Dataset: 
The IRIS dataset is a well-known and frequently used dataset in machine learning and 
statistics. It consists of 150 samples from three species of iris flowers: Setosa, Versicolor, 
Virginica. Each sample has the following four features: Sepal length (in cm), Sepal width (in 
cm), Petal length (in cm), Petal width (in cm). The target variable is the species of the flower, 
where: `0`: Setosa, `1`: Versicolor, `2`: Virginica.  
This dataset is simple and well-balanced, making it ideal for introductory classification tasks 
and model testing. Its clear structure allows for easy interpretation and serves as a foundation 
for understanding more complex datasets and classification challenges. 
### Code: 
The following code utilizes a Gaussian Naive Bayes classifier to classify iris flowers into 
their respective species based on the given features. 
1. Data Loading: The dataset is loaded using `load_iris()` from `sklearn.datasets`, providing 
the data in a structured format. 
2. Preprocessing: The dataset is converted into a pandas DataFrame for easier manipulation. 
The target variable (species) is mapped to its corresponding flower name (Setosa, Versicolor, 
Virginica) for readability. 
3. Data Splitting: The data is split into training and testing sets using `train_test_split()` (70% 
training, 30% testing). 
4. Model Training: The Gaussian Naive Bayes model is initialized and trained on the training 
set. 
5. Model Evaluation:  Predictions are made on the test set. A confusion matrix and a 
classification report are generated to evaluate the model's performance. The accuracy score is 
calculated, and a confusion matrix is plotted for better visualization. 
6. Visualization: The confusion matrix is plotted using `seaborn.heatmap()` to display the 
number of correct and incorrect predictions visually.
### Conclusion 
The Gaussian Naive Bayes classifier is both simple and effective for the IRIS dataset, which 
features continuous variables that align well with this probabilistic model. By successfully 
classifying iris flowers based on sepal and petal dimensions, this project demonstrates the 
potential of machine learning in real-world applications, such as automated plant 
identification and biodiversity assessments. The high accuracy achieved in classifying the iris 
species showcases the model's effectiveness, and the performance metrics provide valuable 
insights into its strengths and limitations. Such classification models can play a crucial role in 
fields like agriculture and ecological research, where accurate species identification is 
essential for informed decision-making and conservation efforts.
