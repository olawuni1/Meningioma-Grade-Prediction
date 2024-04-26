# Meningioma-Grade-Prediction
This project aim to predict the grade of brain tumor (meningioma) in patients based on MRI radiomic features

## Introduction
- Meningioma, the most prevalent primary brain tumor, is categorized by the World Health Organization into grades I, II, or III, with grade I being benign, grade II atypical, and grade III anaplastic.
- The objective of this coursework is to employ machine learning to forecast the grade of meningioma using radiomics features.
- Radiomics features are derived from MRI scans collected from The Cancer Imaging Archive (TCIA), available at https://www.cancerimagingarchive.net/collection/meningioma-seg-class/ under a restricted license agreement.
- The "Target" column denotes the grade of meningioma, while the other columns comprise radiomics features extracted from MRI scans.
The dataset consists of 94 patients diagnosed with meningioma between 2010 and 2019. Meningiomas were categorized as Grade I or Grade II based on the 2016 WHO classification guidelines, with Grade III cases excluded due to their rarity.

## Outline of the python codes

- Preliminary Data Analysis
- Data Standardization
- Feature Selection
- Model Training and Model Evaluation
- Hyperparameter Tuning
- Evaluation of Tuned Models
- Comparing Models Performance

## Conclusion

- Three classification models; logistic regression, naive bayes classifier, decision tree classifier were developed to classify patients to grade I and grade II meningioma category.
- Logistic regression is the best performing model. It has the best accuracy, sensitivity, specificity, precision, recall and AUC.
- Tuning of hyperparameters improve the performance of naive bayes and decision tree while has no effect on logistic revgression.

