# Titanic Survival Prediction

### Description
   This project involves creating and evaluating various machine learning models to predict the survival of passengers on the Titanic. By exploring decision trees, bagged trees, random forests, and boosted trees, this project aims to provide a comprehensive understanding of model performance and feature importance in classification tasks.
Understanding and applying these models is crucial for anyone interested in machine learning, as they form the foundation of many predictive analytics and decision-making processes.

## Table of Contents
1.	Installation
2.	Usage
o	Decision Tree Model
o	Advanced Models
3.	Results
4.	Credits

## Installation

#### To run this project locally, follow these steps:
1.	Clone the repository
    - Go to GitHub and, navigate to the main page of the codingTasks repository.
    - Above the list of files, click  Code.
      
   ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/SheetalKulk/codingTasks/blob/main/Images/1.%20Clone_1%20.png)

 - Copy the URL for the repository.
   - To clone the repository using HTTPS, under "HTTPS", click the copy URL to clipboard icon. 
   - To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click SSH, 
     then click the copy URL to clipboard icon .
   - To clone a repository using GitHub CLI, click GitHub CLI, then click the copy URL to clipboard icon.
     
     ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/SheetalKulk/codingTasks/blob/main/Images/2.%20Clone_2.png)

 - Open Terminal.
 - Change the current working directory to the location where you want the cloned directory.
 - Type git clone, and then paste the URL you copied earlier.

    ##### git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
    
 - Press Enter to create your local clone.

    ##### git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

     ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/SheetalKulk/codingTasks/blob/main/Images/3.%20Clone_3.png)

2.	Install Necessary Modules: Ensure you have Python and Jupyter Notebook installed. You can install necessary packages. 

   - pip3 install pandas
   - pip3 install numpy  
   - pip3 install seaborn
   - pip3 install matplotlib.pyplot
   - pip3 install scikit-learn
   - pip3 install seaborn

Once Installed now we can import it inside our python code.

## Usage

#### Decision Tree Model
1.	Open Jupyter Notebook: Launch Jupyter Notebook and open “decision_tree_titanic.ipynb”.
2.	Follow the Steps:
   o	Data Preparation: Select relevant variables and split the data.
   o	Model Training: Train a decision tree and plot it.
   o	Model Tuning: Experiment with different values of max_depth and store accuracies.
   o	Model Evaluation: Report the final model accuracy on the test data.
  	
3.	Example Plot: 

   ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/SheetalKulk/codingTasks/blob/main/Images/4.%20Plot_1.png)

   ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/SheetalKulk/codingTasks/blob/main/Images/5.%20Plot_2.png)
 
#### Advanced Models
1.	Follow the Steps in the same file:
     - Model Creation: Create bagged trees, random forests, and boosted trees.
     - Feature Importance: Determine the most important feature from the random forest model.
     - Hyperparameter Tuning: Tune n_estimators and max_depth for the Random Forest Classifier model using GridSearchCV. 
     - Model Evaluation: Report the accuracy of the model using best parameters. 
     - Plot: Plot the results for the best parameters.

     ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/SheetalKulk/codingTasks/blob/main/Images/6.%20Plot_3.png)
 
    - Model Comparison: Report and compare the accuracy of all models.
    
2.	Comparison: 

 ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/SheetalKulk/codingTasks/blob/main/Images/7%20-%20Accuracy.png)

## Results
  •	The notebooks provide insights into the performance of each model through various plots and accuracy reports.
  •	Feature importance analysis helps in identifying which factors are most influential in predicting survival.
  •	Comparing models aids in selecting the best-performing model with optimal parameters.

## Credits
 This project was developed by Sheetal Kulkarni. This project was developed as a part of one of the tasks by HyperionDev. 
