Fraud Detection in Bank Transaction
=================


repo for documentation my personal project in fraud detection  

For Fraud detection i'm using Random Forest methods


**Random Forest** is are an ensemble learning method for classification, regression and other tasks 
that operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes (classification)
or mean prediction (regression) of the individual trees


This step what i've done:
- Remove unuseful data like near-zero-varianceâdata or magic values (non-logic sense data)
- Impute missing values with Amelia & missforest packages, remove the duplicates data
- make a feature cross, A feature cross is a synthetic feature formed by multiplying (crossing) two or more features
- check variable/feature distribution  by histogram plot
- Check correlation between features
- Use Binary encoding for large categoricak features
- normalize data for continous features
- balance the data using ubSMOTE
- make model with RF methods


I've got AUC = 0,687; accuracy = 91,4% but recall is very low only 1.9% <-- i hope can fixed my model



**Screenshot**

![](https://cdn.glitch.com/38fb7291-b561-4f55-b133-1dbaaabc47d8%2FWhatsApp%20Image%202019-06-19%20at%2002.32.22.jpeg?v=1560886424782)
![](https://cdn.glitch.com/38fb7291-b561-4f55-b133-1dbaaabc47d8%2FWhatsApp%20Image%202019-06-19%20at%2002.32.21.jpeg?v=1560886424744)
![](https://cdn.glitch.com/38fb7291-b561-4f55-b133-1dbaaabc47d8%2FWhatsApp%20Image%202019-06-19%20at%2002.32.20.jpeg?v=1560886425630)
![](https://cdn.glitch.com/38fb7291-b561-4f55-b133-1dbaaabc47d8%2FWhatsApp%20Image%202019-06-19%20at%2002.32.21%20(1).jpeg?v=1560886425120)