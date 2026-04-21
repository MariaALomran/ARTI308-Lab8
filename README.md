# ARTI308-Lab8
 KNN Classification

The project focuses on categorizing data points into predefined classes using the K-Nearest Neighbors (KNN) algorithm. The model determines the class of a data point by measuring its similarity, typically through distance, to its closest neighbors. The workflow involves data preprocessing, training the model, evaluating its performance, and fine-tuning the value of K for optimal results.

Dataset used:
KNN_Project_Data.csv

it includes numerical features along with:

TARGET CLASS – Target variable (1 or 0)

paraphrase EDA
Data visualization was performed to understand patterns and relationships:

Pair plots to visualize relationships between features
Analysis of feature distribution
Observing class separation based on TARGET CLASS

 Data Preparation
Performed feature scaling using StandardScaler because KNN is distance-based

Selected all numerical features for training

Split dataset into:
Training set is 70%
Testing set is 30%

 Model
Algorithm: K-Nearest Neighbors (KNN)
Library: Scikit-Learn

Initial parameter:
K = 1
Then optimized K value by testing values from 1 to 40

Performance
Model performance improved after tuning:

K = 1 → Accuracy ≈ 72%
K = 30 → Accuracy ≈ 83%

Technologies Used are:
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Python

Conclusion : The KNN model achieved improved results after identifying an optimal value for K. Applying feature scaling significantly enhanced accuracy, as it ensured fair distance comparisons. Selecting an appropriate K value is essential to maintain a balance between overfitting and the model’s ability to generalize well.

✅ Conclusion
The KNN model showed better performance after selecting the optimal K value. Feature scaling played a critical role in improving accuracy. Choosing the right K helps balance between overfitting and generalization.
