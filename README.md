# Extending_linear_models_limitations

In this file, it contains 5 ipython notebooks, You can use google colab or jupter to open these files in the system.
All the data sets needed in order to run the notebooks are uploade in this repo.

## 1. Implementing_platt_scalling_to_find_p(x==1).ipynb

PLATT SCALING : platt scaling is a method used to transform outputs of classification model into probability distrubution over classes.
#https://www.analyticsvidhya.com/blog/2016/07/platt-scaling-isotonic-regression-minimize-logloss-error/

Here in this ipython nodebook we created a custom decision function of SVM RBF KERNEL
and we comapred the results with the outputs of sklearn implementaion
and in order to implement plat scaling to find p(x==1) we change y+,y- values (clearly explained in notebook) to avoid over fitting.

## 2.LR_&_SVM_on_correlation_data.ipynb

For this task we used a correlated data and we applied both Logistic regression(SGDClassifier with logloss) and SVM(SGDClassifier with hinge)
before and after standralizing the data. And observations are mentioned in the notebook.

## 3.LR_&_SVM_on_imabalced_data.ipynb

We had created 4 data sets (2 classes) with ration of 100:2,100:20,100:40,100:80 and applied svm , logistic regression with different variations 
and observed which model performs better on imbalnce data . the visual representation mentioned in the ipython notebook.

## 4.effect_of_SVM_on_outliers.ipynb

In this notebook we have observed how SVM performs on outlier data .( with visual representation) 
as part we had created data with ellipse structure (as the seperating line of svm passes through its centre .
and introduced outlier from small amount to huge and observe the change in plane 
the visual representaition is mentioned in the ipython notebook.

## 5.effect_of_linear_models_on_collinear_data.ipynb

we had used custom dataset (d.csv) which has collinear data and observed how logistic repression and svm performed ( with their best hyperparameters)


# thankyou
