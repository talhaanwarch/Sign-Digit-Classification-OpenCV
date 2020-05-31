# Sign-Digit-Classification-OpenCV
Sign language digit classification with sklearn hog and svm and live testing with opencv camera.

Dataset is taken from https://github.com/ardamavi/Sign-Language-Digits-Dataset  

First histogram of oriented gradients (HOG) are calculated from all images, then these features are reduced by Principle component analysis.
An accuracy of 90% is achieved using 5 fold cross validation. # Uncomment the line 30.

![Demo](signs_testing_opencv.gif)

