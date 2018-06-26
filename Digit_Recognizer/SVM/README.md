# Digit Recognizer using SVM

Though SVM is not the preferred choice for this competition on kaggle but it is most sensitive to parameter tuning in SVM.

### Training Data Set

The training data has shape (42000, 785). The first column is the label and rest 784 columns are stratified(by row) (28,28) grayscale images with
values ranging from 0-255. The label column specifies which digit is represented by input image. As SVM are computationally heavy I will take subset of the training data to train our SVM model as I am low on computation power :sob:
.
