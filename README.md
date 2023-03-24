
PYTHON PROJECT USING MACHINE LEARNING

# Breast-cancer
------------------------------------------------------------------------------------------------------------------------------------------------------
One of the most widespread health issues in the globe is breast cancer.About 8% of women are diagnosed with breast cancer (BC) over their lifetime, second only 
to lung cancer.
The most common categorization for breast cancer is binary (benign cancer/malign cancer), 
which helps pathologists discover a systematic and objective prognosis.
In this machine learning project, we will study and categorise breast cancer (which group it 
falls under), as there are primarily two types of breast cancer:
-> Breast cancer of the malignant 
 -> Benign variety
 
 IMAGES:
 ![PIC1](https://user-images.githubusercontent.com/111978576/227541474-1ddad47b-89e5-46da-b5cf-aa0a40104880.PNG)
![TUMORIMG](https://user-images.githubusercontent.com/111978576/227541487-90761c96-21fd-4c99-b417-affaceace340.PNG)

KEYWORDS:
Classification of benign and malignant breast cancer , Logistic Pre-Processing, Train, Test,
Split, Datapre-processing , Breast cancer dataset, Numpy , Pandas, model selection

 THE DATASET
We will be using a dataset on breast cancer from Sklearn.
We will thoroughly study the dataset, which will answer all of the queries about the 
dataset we will use, the no. of columns and rows etc. Consequently, there are 30 
columns that are:
• Mean Radius
• Mean Texture
• Mean Perimeter
• Mean Area
• Mean Smoothness
• Mean Compactness
• Mean Concavity
• Mean Concave Points
• Mean Symmetry
• Mean Fractal Dimension
• Radius Error
• Texture Error
• Perimeter Error
• Area Error
• Smoothness Error
• Compactness Error
• Concavity Error
• Concave Points Error
• Symmetry Error
• Fractal Dimension Error
• Worst Radius
• Worst Texture
• Worst Perimeter
• Worst Area
• Worst Smoothness
• Worst Compactness
• Worst Concavity
• Worst Concave Points
• Worst Symmetry
• Worst Fractal Dimension
• LabeL
DATASET
o A type of biopsy procedure known as fine needle aspiration involves inserting a thin 
needle into the area of tissue that appears abnormal. This technique can be used to 
diagnose conditions like cancer.
o Breast Cancer Dataset is taken from sk.learn datasets.
o breast_cancer_dataset = sklearn.datasets.load_breast_cancer()

RESULT :
The trained data is evaluated and therefore classified in Benign and Malignant.
 0 represents Malignant
 1 represents Benign
Evaluation is done using the accuracy score() which tells the accuracy of the
classification.
 Accuracy on training data = 0.9472527472527472
 Accuracy on test data = 0.9210526315789473

CONCLUSION AND NEXT WORK :
 The best collection of characteristics that predict breast cancer were selected 
for this study using the logistic regression approach.
Using a logistic regression model, we were able to create a method for categorising
breast cancer that is fairly accurate and useful for recognising the main types of breast
cancer.Major health risks can be avoided and even lives may be saved through the 
early detection and treatment of various conditions.
Our model has a 94.8% training data accuracy and a 92.9% testing data accuracy.
Our model is identifying test data quite effectively and precisely, as we have already
witnessed.As a result, using the Numpy and pandas libraries, we have learned how 
to analyse and visualise data.
One needs to be familiar with machine learning principles and the Python language to
make this project work.
This project effectively distinguishes which one is benign and which is malignant 
breast cancer.
To obtain an accurate result, a total of 30 columns from the obtained dataset were 
used. The algorithm classifies the data into benign and malignant once the 
characteristics have been retrieved and fully trained.
In the future, we will be able to provide a picture as an input instead of numerical 
data, and the classifier will then have to determine if the image is benign or cancerous 
before classifying it.
