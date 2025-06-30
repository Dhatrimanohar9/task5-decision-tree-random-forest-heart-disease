#  Heart Disease Prediction using Decision Trees & Random Forests

This project was completed as part of **Task 5** of the AI & ML Internship.  
The goal was to build tree-based classification models to predict whether a patient has heart disease.


## Objective

- Train and visualize a **Decision Tree Classifier**
- Analyze and tune for **overfitting** using `max_depth`
- Build a **Random Forest Classifier** and compare its accuracy
- Interpret **feature importances**
- Evaluate the model using **cross-validation**


## Files in This Repo

- `heart.csv` – Dataset used for training
- `Task5_DecisionTrees_RandomForest_HeartDisease.ipynb` – Jupyter Notebook with full implementation
- `README.md` – You're reading it!



##  Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn



##  What’s Inside the Notebook?

###  1. Data Preprocessing
- Cleaned and split the data into features (`X`) and target (`y`)
- Applied `train_test_split` for model training

###  2. Decision Tree Classifier
- Trained a basic decision tree
- Evaluated with **accuracy**, **confusion matrix**, and **classification report**
- Visualized the full tree using `plot_tree()`
- Tuned `max_depth` to control overfitting and improve generalization

###  3. Random Forest Classifier
- Trained an ensemble of decision trees
- Compared accuracy with the single decision tree
- Plotted **feature importances** to interpret the model

###  4. Cross-Validation
- Performed **5-fold cross-validation** for model reliability


##  Sample Output 
Decision Tree Accuracy: 0.80
Random Forest Accuracy: 0.86
Mean CV Accuracy: 0.84


##  Key Takeaways

- Random Forest generally performs better than a single Decision Tree.
- Tuning `max_depth` helps avoid overfitting.
- `cp`, `thalach`, and `exang` were among the most important features for prediction.
- Cross-validation helps evaluate model stability.



##  Dataset Source

- [Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)



##  Submission Info

This notebook is submitted as part of **Task 5: Decision Trees and Random Forests**  
under the AI & ML Internship Program.




