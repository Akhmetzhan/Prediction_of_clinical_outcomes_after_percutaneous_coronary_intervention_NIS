# Prediction_of_clinical_outcomes_after_percutaneous_coronary_intervention_NIS
The repository includes open-access R and Python codes related to the paper "Prediction of clinical outcomes after percutaneous coronary intervention: machine-learning analysis of the National Inpatient Sample".

Abstract

Background: This study aimed to develop a multiclass machine-learning (ML) model to predict all-cause mortality, ischemic and hemorrhagic events in unselected hospitalized patients undergoing percutaneous coronary intervention (PCI).

Methods: This retrospective study included 1,815,595 unselected weighted hospitalizations undergoing PCI from the National Inpatient Sample (2016-2019). Five most common ML algorithms (logistic regression, support vector machine (SVM), naive Bayes, random forest (RF), and extreme gradient boosting (XGBoost)) were trained and tested with 101 input features. The study endpoints were different combinations of all-cause mortality, ischemic cerebrovascular events (CVE) and major bleeding. An area under the curve (AUC) with 95% confidence interval (95% CI) was selected as a performance metric.

Results: The study population was split to a training cohort of 1,186,880 PCI discharges, validation cohort (for calibration) of 296,725 hospitalizations and a test cohort of 331,990 PCI discharges. A total of 98,180 (5.4%) hospital entries included study outcomes. Logistic regression, SVM, naive Bayes, and RF model demonstrated AUCs of 0.83 (95% CI 0.82-0.84), 0.84 (95% CI 0.83-0.86), 0.81 (95% CI 0.80-0.82), and 0.83 (95% CI 0.81-0.84), retrospectively. The XGBoost classifier performed the best with an AUC of 0.86 (95% CI 0.85-0.87) with an excellent calibration. We then built a web-based application that provides predictions based on the XGBoost model.

Conclusion: We derived the multi-task XGBoost classifier based on 101 features to predict different combinations of all-cause death, ischemic CVE and major bleeding. Such models may be useful in benchmarking and risk prediction using routinely collected administrative data.
