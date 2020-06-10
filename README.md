# Sign-Digit-Classification-OpenCV
Sign language digit classification with sklearn hog and svm and live testing with opencv camera.


# Notebooks
There are two files jupyter notebook files
1. [finger_count.ipynb](finger_count.ipynb)
2. [sign_language_classification.ipynb](sign_language_classification.ipynb)

* For [file 1](finger_count.ipynb), i was trying to count fingers of hand using open cv, no machine learning is involved. Simply click on run all and it will start working
* For [file 2](sign_language_classification.ipynb), hog features are calculated and principle component analysis is used for hog feature
reduction. Data is available in [Dataset.zip](Dataset.zip) . Unzip the data and set path according to your directory and run it. 
An accuracy of 90% is achieved using 5 fold cross validation. # Uncomment the line 30.

I tried to use both hand in non machine learning based finger count to count from 1-10 but thats bit noisy , the right frame showing noise instead of clear background as compared to left frame. Thats make the counting bit inaccurate when both hands are used. Check demo 3


<!---![Demo](signs_testing_opencv.gif)--->
# Packages used
OpenCv - 4.2.0  
Numpy  
Sklearn  
Skimage - 0.16.2  
matplotlib  
os  
glob  

## Machine Learning based finger count  Demo
![Demo1](ml_final.gif)

## Non Machine Learning based finger count  Demo
![Demo1](cv_final.gif)

## Non Machine Learning based Both hands finger count  Demo
![Demo1](both_hands.gif)

# Data source
Dataset is taken from https://github.com/ardamavi/Sign-Language-Digits-Dataset  
