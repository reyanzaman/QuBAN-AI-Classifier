# QuBAN-AI-Classifier
Multinomial naive bayes classifier for QuBAN dataset of questions to classify topics and courses for questions asked by students.

Dataset is publicly available for use at:
## https://doi.org/10.5281/zenodo.10051055

The dataset contains scored questions on topics of CIS101 (Fundamentals of Computer & Research) and CSC203 (Data Structure). The questions are categorized by their topics and courses and also the irrelevant questions are seperated from the relevant ones.

The dataset is a part of the QuBAN Research Paper which is included as a pdf file.

Code is available to use on colab:

# Sample Results

QuBAN Topic Classifier:
## https://colab.research.google.com/drive/1hllCDYPGh5lFuwK3lRjE89xTjc18HxIZ?usp=sharing

QuBAN Course Classifier:
## https://colab.research.google.com/drive/1o5iTyCaEOKJ4MiqbVWG-euyCSHu80bll?usp=sharing

Accuracy of CSC203 course classifier compared with changing random state variable to randomly select data for training and test datasets.
![Random State Accuracy](results/A.png?raw=true "Random State Accuracy")

Accuracy of CSC203 course classifier compared with test dataset percentage size.
![Test Size Accuracy](results/B.png?raw=true "Test Size Accuracy")

3D Plot of the accuracy of CSC203 course classifier compared with test dataset percentage size and random state variable.
![3D Plot Accuracy](results/C.png?raw=true "3D Plot Accuracy")

Smoothed 3D Plot of accuracy of CSC203 course classifier compared with test dataset percentage size variable.
![3D Smoothed Plot Accuracy](results/D.png?raw=true "3D Smoothed Plot Accuracy")
