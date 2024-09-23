# Credit Risk Analysis Report

## **Overview**

Use machine learning to train and evaluate a model based on loan risk. Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

</br>

* Using a machine learning model to determine which loans are healthy or high-risk based on the loan status provided by the lending company. 

  * The Logistic Regression Algorithm is the best tool to use. 

</br>

```
# code
y.value_counts()

# output
0    75036
1     2500
Name: loan_status, dtype: int64
```

</br>

## **The Results**

</br>

* Accuracy Score: 99%
* Precision Scores: 100% for healthy loans; 84% for high-risk loans
* Recall Scores: 99% for healthy loans; 94% for high-risk loans

</br>

## **Summary**

* A lending company might want a model that requires classifying healthy and high-risk loans correctly most of the time: 

    * healthy loans being identified as a high-risk loan might be more costly for a lending company since it might cause the loss of customers. 
  
    * high-risk loans being identified as a healthy loan might also be more costly for a lending company due to the loss of funds being provided by the lender.

</br>

* The lending company would most likely want fewer False Positives due to the high possibility of a lender loosing provided funds when classifying high-risk loans as healthy. The data below is shown in the confusion matrix:
  
  * 36 (FALSE POSITIVES)


  * 110 (FALSE NEGATIVES)

</br>
  
According to the confusion matrix and all the results given above, I would recommend using the model.

---
