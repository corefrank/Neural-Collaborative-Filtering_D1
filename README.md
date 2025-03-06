# Expected work
- Implement at least MF with ALS or Gradient Descent
- Implement one/several alternative method of your choice
LSH, PCA, Optimal transport, etc.
- Write a small report & present your work to the class
  - Discuss hyperparameter tuning (e.g. how to set k)
  - Discuss how to incorporate genre (or other features)
  - Theoretical comparison vs. baseline
  - Experimental comparison vs. baseline



# Teammate
Nan An
Othman Hicheur
Kanupriya Jain



[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/D8_KJwUP)
# DataLabAssignement1

## generate.py
Use the file *generate.py* to complete your ratings table. 
It takes in argument *--name* the name of the files you want to use and it saves the complete matrix as *output.npy*.
DO NOT CHANGE THE LINES TO LOAD AND SAVE THE TABLE. Between those to you are free to use any method for matrix completion. 
Example:
  > python3 generate.py --name ratings_train.npy

## requirements.txt
Among the good pratice of datascience, we encourage you to use conda or virtualenv to create python environment. 
To test your code on our platform, you are required to update the *requirements.txt*, with the different librairies you might use. 
When your code will be test, we will execute: 
  > pip install -r requirements.txt
