# 2nd Year Undergraduate Computational Project (2022)
 
## Classifier to predict the crystalline structure of Perovskites with Machine learning.

### Written by Karen Pacho Dominguez, Navraj Eari, Rushvi Shah and Siddharth Puri | as part of our submission for the "MATE50001 - Mathematics and Computing 2 2021-2022" module.

- A database of 4,165 ABO3 perovskites, each with 13 differernt of features such as bond length, electronegativities, and goldschmidt factors, was provided by an article on computational material science[1], which we used as our population data.
- **Notebook 1:** Contains preprocessing of population dataset, test-train-split, KNN, SVC, and Random Forst classifaction alogrithms, and optimisation of hyperparameters.
- **Notebook 2:** Explanation of our methodolgy in Notebook 1 (why we performed certain preprocessing steps, physical relavence, conclusions drawn from each algorithm etc).
- **Notebook 3:** Visualisation of the classifaction in the form of an interactive confusion matrix (or heat map) plot. Also provides numerical values such as the F1 score and accuracy.

<img width="471" alt="Screenshot 2022-07-08 153319" src="https://user-images.githubusercontent.com/102254245/178013220-5d4370ab-3c36-4d18-840b-2cad54066e90.png">

- Displays the predicted classifaction (the ones the alogorithmn calculated) against the actual classifaction (the true one, provided in the dataset). Therefore diagonal elements are desired.
- Abilty to remove a parameter via the box on the right, and observe how the accuracy of the classifer changes.

- To use, run the Juypter notebook. Ensure all files are in the same directory.

[1] - Santosh Behara, Taher Poonawala, Tiju Thomas, Crystal structure classification in ABO3 perovskites via machine learning, Computational Materials Science,
Volume 188, 2021, 110191,
ISSN 0927-0256,
(https://www.sciencedirect.com/science/article/pii/S0927025620306820)
