# Breast_Cancer_Wisconsin_Diagnostic-SVM

### **Task:** Predict whether the cancer is benign or malignant using SVM

### **Trained Model:** Accuracy: 97%
### **Dataset available on:** [UCI Machine Learning Breast Cancer Wisconsin (Diagnostic)](http://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic) , [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

**Developers' Guide:** [Amazon Machine Learning](https://docs.aws.amazon.com/pdfs/machine-learning/latest/dg/machinelearning-dg.pdf#cross-validation)                                             
**Link to the notebook:** [Breast Cancer Wisconsin (Diagnostic)-SVM](https://github.com/Kmohamedalie/Breast_Cancer_Wisconsin_Diagnostic-SVM/blob/master/Notebook/Breast_Cancer_Wisconsin_(Diagnostic)_SVM.ipynb)
#### **[The Guardian: AI system outperforms experts in spotting breast cancer](https://www.theguardian.com/society/2020/jan/01/ai-system-outperforms-experts-in-spotting-breast-cancer)**
![image](https://github.com/Kmohamedalie/Breast_Cancer_Wisconsin_Diagnostic-SVM/assets/63104472/e231dabe-a120-4d51-ba84-137f3741396d)

### **About Dataset:** <br>
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. <br>
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34]. <br>

This database is also available through the UW CS ftp server:  <br> 

ftp ftp.cs.wisc.edu    <br>

cd math-prog/cpo-dataset/machine-learn/WDBC/   <br>

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 <br>

Attribute Information:

1) ID number <br>
2) Diagnosis (M = malignant, B = benign)
3-32)

<br>
Ten real-valued features are computed for each cell nucleus:  <br>

a) radius (mean of distances from center to points on the perimeter)  <br>
b) texture (standard deviation of gray-scale values)   <br>
c) perimeter    <br>
d) area     <br>
e) smoothness (local variation in radius lengths)    <br>
f) compactness (perimeter^2 / area - 1.0)         <br>
g) concavity (severity of concave portions of the contour)    <br>
h) concave points (number of concave portions of the contour)     <br>
i) symmetry      <br>
j) fractal dimension ("coastline approximation" - 1)      <br>

The mean, standard error and "worst" or largest (mean of the three     <br>
largest values) of these features were computed for each image,        <br>
resulting in 30 features. For instance, field 3 is Mean Radius, field       <br>
13 is Radius SE, field 23 is Worst Radius.                                 <br>
    
All feature values are recoded with four significant digits.                 <br>

Missing attribute values: none                                                  <br>

### Class distribution: 357 benign, 212 malignant
