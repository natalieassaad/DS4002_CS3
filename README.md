# DS4002_CS3

## Spam or Ham Identification Case Study 
This repository includes all materials necessary to replicate this study on spam or ham email detection. The goal of this project is to produce three machine learning models (K-Nearest Neighbors, Logistic Regression, and Decision Trees) and evaluate model performance based on precision and accuracy to determine which model is most effective at identifying spam emails. 

## Background Materials 
The [hook document](https://github.com/natalieassaad/DS4002_CS3/blob/main/Hook%20Document_Spam%20Ham%20Detection.pdf) contains the motivation behind this case study and a brief explanation of the deliverables. The [rubric](https://github.com/natalieassaad/DS4002_CS3/blob/main/Rubric_Spam%20Ham%20Detection.pdf) includes a description for each component necessary for completion of the case study. Finally, this repository also contains various reference materials that will help with completing the code. Please find these materials in [REFERENCE FILES](https://github.com/natalieassaad/DS4002_CS3/tree/main/REFERENCE%20FILES). This folder includes a brief blog post providing background information on spam/the importance of combatting this issue. The folder also includes two technical articles from Medium that will be helpful in completing the code. 

## Data 
The datasets used in this case study can be found in the DATA folder. This includes the original dataset ([emails.csv](https://github.com/natalieassaad/DS4002_CS3/blob/main/DATA/emails.csv)) and an example CSV file of final results ([example_model_results.csv](https://github.com/natalieassaad/DS4002_CS3/blob/main/DATA/example_model_results.csv)). 

## Code 
In the CODE folder, you will find the [PreprocessingScript_EDA.ipynb](https://github.com/natalieassaad/DS4002_CS3/blob/main/CODE/PreprocessingScript_EDA.ipynb) file which must be run in order to clean/preprocess the textual data. The file already contains prewritten data cleaning/EDA code, but you will have to fill in the textual preprocessing code. After completing this script and exporting the preprocessed_data.csv, use [AnalysisScript.ipynb](https://github.com/natalieassaad/DS4002_CS3/blob/main/CODE/AnalysisScript.ipynb) to run and complete the code for the analysis. In this script, you will have to complete the code for the KNN and Decision Tree models. You will then export the graphs and tables produced at the end of the analysis to evaluate the model performance.

## References 
[1] H. Caldwell, “The impact of spam emails on businesses,” Texaport, https://texaport.co.uk/blog/the-impact-of-spam-emails-on-businesses#:~:text=Spam%20is%20a%20blanket%20term,protect%20their%20data%20and%20privacy. (accessed Apr. 27, 2025). 

[2] Sudipakoner, “Building a spam email detection model: A step-by-step guide,” Medium, https://medium.com/@sudipakoner492/building-a-spam-email-detection-model-a-step-by-step-guide-aa44e7ff9b21 (accessed Apr. 27, 2025). 

[3] A. Khan, “Email spam detection with Machine Learning: A Comprehensive Guide,” Medium, https://medium.com/@azimkhan8018/email-spam-detection-with-machine-learning-a-comprehensive-guide-b65c6936678b (accessed Apr. 27, 2025). 
