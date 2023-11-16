# To-Do:

* Get R**2 for logistical regresion model

# Notes:

* Predicting network attacks
* are each packet correlated to each other or are they independent
* tree based method to predict whether its malicious then use classification for which type
* Linear discriminant analysis
* quadratic discriminant analysis
* K-nearest neighbors
* If two variables are highly correlated one can be removed.
* Confusion matrix for determining thee best classification model (regression)
* PCA (method to elegantly reduce number of variables)

# Questions

* forward selection
* where would i note in the report all of the features of the dataset? in the methods chapters? (no results)
* eploratory data analysis, (build hypothesis and write explanations based on graphs and plots) (think about what you want to say and use what is needed to say it.)
* Write about preprocessing
* Write your entire (or as much of your) process leading to the result gotten
* Later answer the hypothesis based on the graphs (e.g. wrong_fragment is a highly determinative feature)
* Have code present in the report?

# Sources and links:

* https://www.nature.com/articles/s41598-021-91805-z
* https://www.kaggle.com/datasets/anushonkar/network-anamoly-detection
* https://blog.dataiku.com/tree-based-models-how-they-work-in-plain-english

# Additional sources and links:

* https://www.kaggle.com/datasets/asfandyar250/network (general network from ISP can be used later to check perhaps)
* https://www.kaggle.com/datasets/hawkcurry/2019-trendmicro-ctf-wildcard-400 (regarding general network security)

# Important features

* wrong_fragments
* src_bytes
* service
* last_flag
* flag
* protocol_type
* serror_rate

# Unimportant features

* land

# Report structure

* Title
* Abstract
* Introduction

- what is the problem?
- what is the dataset
  - where is it from
  - what does it contain
- what is the level of confidence
- outline

* Methods

- What tools used and why
- What features used and why (RSS)
- What model used and why (AIC, BIC,...)
- How is the model trained
- Summary of chapter

* Results

- feature selection and elimination
- accuracy
- interperability
- Summary of chapter

* Discussion

- is the dataset more accurate than the level of confidence?
- Discuss result
- Good feature?
- Good model?
- Overfitting?
- Relevant dataset?
- Summary of chapter

* Conclusion
