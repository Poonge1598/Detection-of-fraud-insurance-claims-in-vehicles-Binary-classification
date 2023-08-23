# Detection of Fraudulent Insurance Claims in Vehicles - Binary Classification

This project focuses on detecting fraudulent insurance claims in the context of vehicles. Various supervised machine learning models were employed for this task, including Logistic Regression, Support Vector Machines (SVM), Random Forest, and XGBoost. The goal was to classify whether a given record could be categorized as fraudulent based on its characteristics. The classification threshold was optimized to maximize the Youden score and F1-score.

## Models Explored

Several supervised machine learning models were evaluated:

- **Logistic Regression**
- **Support Vector Machines (SVM)**
- **Random Forest**
- **XGBoost**

## Key Findings

- All models model achieved a good accuracy score of over 90%.
- One common challenge was achieving a high recall without sacrificing overall accuracy.
- Achieving a good recall often required setting very low classification thresholds.
- The choice of threshold significantly impacted model performance and trade-offs.

## Conclusion

After thorough evaluation and comparison of the models, several insights were gained:

- Despite high accuracy, models struggled to achieve good recall without using very low thresholds.
- Extremely low thresholds led to a notable decrease in overall accuracy due to an increase in false positives.
- The XGBoost model with selected features stood out as the final choice due to its balanced performance.
- By selecting a threshold that optimized the F1-score or Youden score, the XGBoost model achieved a compelling recall of 85.9% while maintaining an acceptable accuracy.
- The threshold decision would ultimately depend on real-world scenarios and priorities. For instance, a higher recall might be favored over overall accuracy in cases where correctly identifying fraud is paramount.

This project highlights the intricacies of balancing accuracy and recall in fraud detection scenarios and provides valuable insights into the performance of various machine learning models.
