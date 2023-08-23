# Detection-of-fraud-insurance-claims-in-vehicles-Binary-classification

#Employed several supervised machine learning models such as logistic regression,Support vector machines(SVM),random forest and XG-boost to classify whether a particular record could be classified as fraudulent or not depending on its characteristics.Optimised threshold based on which yields the best youden score,f-1 score.

#Conclusion:
#After reporting all the results and evaluations, we can see that all models – despite a good accuracy score over 0.9 – always struggles to reach a good recall, unless very low classification thresholds are chosen. Nevertheless, this has a drawback, with huge decreases in overall accuracy, especially using SVM with selected features, with the number false positives that exceed true negatives’ one. As our final model, we would choose the XG-boost using selected features, probably selecting the threshold that maximizes the F1-score/youden score; in fact, with even lower thresholds, the model classified too many false positives, obtaining a low accuracy of 0.6744. On the other hand, with 0.05 as threshold, the model reaches a recall of 0.859, identifying almost all fraud correctly. At the end, the threshold choice would depend on a real casescenario, where – for example – we might want to get a high recall regardless the overall accuracy

