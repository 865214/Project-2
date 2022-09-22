# Project-2

# Objective
The document classification solution should significantly reduce the manual human effort in the HRM .It should achieve a higher level of accuracy and automation with minimal human intervention.

# Textract
This package provides a single interface for extracting content from any type of file, without any irrelevant markup.
![image](https://user-images.githubusercontent.com/101926069/191774047-5e0cea88-1f36-4172-9ca8-67f21ba10a66.png)

# Converting all file to .txt (Process)
![image](https://user-images.githubusercontent.com/101926069/191774289-67b7fea7-fead-4feb-af81-bc8121864066.png)

# Merging all category files
![image](https://user-images.githubusercontent.com/101926069/191774534-c128a362-874c-4bf8-9186-f1ec4285a5fc.png)

# Converting text to .csv (Process)
![image](https://user-images.githubusercontent.com/101926069/191774826-14105151-31b1-48f9-bb1b-2cd2dd1b6c99.png)

# Data Set Details
After Extracting and Modifying the Dataset, given data contains a total of 4 Classes and 79 rows . 
![image](https://user-images.githubusercontent.com/101926069/191775189-00292a4d-f482-4362-a5a4-05ec070bce2a.png)
![image](https://user-images.githubusercontent.com/101926069/191775280-eeb2f7f6-802e-4b7f-a92a-19e61b157d43.png)

# Removing All Unwanted Character’s
Unwanted Character’s like - \n \t, http links, tags, hashtags, html tags, converting to lower case, removing white spaces etc.
Word Tokenization - Tokenization is essentially splitting a phrase, sentence, paragraph, or an entire text document into smaller units, such as individual words or terms. Each of these smaller units are called tokens.
Removing Stop-words - A stop word is a commonly used word (such as “the”, “a”, “an”, “in”) that a search engine has been programmed to ignore, both when indexing entries for searching and when retrieving them as the result of a search query.
![image](https://user-images.githubusercontent.com/101926069/191775515-b54d836b-d38f-4859-bdab-3f733f643ce0.png)

# Text – Preprocessing
![image](https://user-images.githubusercontent.com/101926069/191775832-16baad2d-8502-48d1-9c59-915e549c174d.png)
![image](https://user-images.githubusercontent.com/101926069/191775880-10083804-432e-4878-bc34-84012665591c.png)
In natural language processing, text preprocessing is the practice of cleaning and preparing text data. NLTK and re are common Python libraries used to handle many text preprocessing tasks.
The Dataset contains 79 rows and 3 Column 
There are total four Classes – Peoplesoft, Workday, React JS Developer and SQL Developer.
![image](https://user-images.githubusercontent.com/101926069/191776257-afe1fb64-47d3-4941-8f1c-375aac5562ec.png)

# Labels
By using Pie chart roles applied feature is displayed to visualize the job roles.
![image](https://user-images.githubusercontent.com/101926069/191776750-5848dfb7-95d8-454c-8434-b2016dbb0aa9.png)
By using Histogram  roles applied feature is displayed to check the job types.
![image](https://user-images.githubusercontent.com/101926069/191777001-bafdc60d-1620-439a-815b-eeb90f4a3aaa.png)

# Word Cloud
![image](https://user-images.githubusercontent.com/101926069/191777149-34369ae3-95a7-4830-a102-44169c79e6de.png)

# TF-IDF
![image](https://user-images.githubusercontent.com/101926069/191777348-ec3e0eaf-e1d4-44b0-8e87-e4225b242c79.png)![image](https://user-images.githubusercontent.com/101926069/191777414-9d5bf23b-245b-465e-84e7-033e6b5b9c92.png)
TF-IDF is better than Count Vectorizers because it not only focuses on the frequency of words present in the corpus but also provides the importance of the words.We can then remove the words that are less important for analysis, hence making the model building less complex by reducing the input dimensions.

# Train-Test Split
![image](https://user-images.githubusercontent.com/101926069/191778132-ff739609-03a4-49d4-92ea-54fa0a335775.png)
![image](https://user-images.githubusercontent.com/101926069/191778204-0115ec57-5d83-4f1f-a32d-eed5c8676ab4.png)

# Confusion Matrix
Before Stratified Sampling
![image](https://user-images.githubusercontent.com/101926069/191778552-34d15d6b-c724-43ac-860c-f0ab4fec177a.png)
After Stratified Sampling 
![image](https://user-images.githubusercontent.com/101926069/191778674-d89a8648-2e12-426e-8bbc-4ce4c87346c3.png)

# Model Building 
![image](https://user-images.githubusercontent.com/101926069/191778877-f03e2fd0-1736-4eaa-9a8e-2ba8ca79964a.png)

# Model Evaluation
![image](https://user-images.githubusercontent.com/101926069/191779022-ba28db9c-47a7-477e-afc8-a7ce5814fcc3.png)
Here, we have taken Model building algorithms such as Decision Tree Classifier,  Logistic Regression, SVM, Random , Forest, etc.Among these algorithms, 100% Accuracy, Precision, Recall and F1-score have been achieved.100% accuracy is achieved by using the model Random Forest, Decision Tree and Gradient Boosting Classifier.
Here, we have taken Model building algorithms such as Decision Tree Classifier,  Logistic Regression, SVM, Random , Forest, etc.Among these algorithms, 100% Accuracy, Precision, Recall and F1-score have been achieved.100% accuracy is achieved by using the model Random Forest, Decision Tree and Gradient Boosting Classifier.
![image](https://user-images.githubusercontent.com/101926069/191779500-aaf9eac0-5d24-49d6-a95b-f01724ea7c8d.png)
![image](https://user-images.githubusercontent.com/101926069/191780884-0d3f107f-84ba-4572-8d4e-1c4f75dd70df.png)

#  Model Evaluation Report
Random Forest Classifier
![image](https://user-images.githubusercontent.com/101926069/191781130-5faa7f4c-f9aa-4324-84a4-6a9b7bee4efa.png)
![image](https://user-images.githubusercontent.com/101926069/191781218-7c0fdd03-04ee-4f78-9644-5fd77534e0f4.png)
Here, we have taken Random Forest Model.100% Accuracy, Precision, Recall and F1-score have been achieved.No overfitting or underfitting has been found. All classes are classified correctly and no misclassification.

# Deployment
![image](https://user-images.githubusercontent.com/101926069/191781591-694575ec-4bf9-465f-87a8-d07b5125b9b0.png)
Here, we have taken Random Forest as our Final Model algorithms for the deployment.The algorithm has achieved 100% Accuracy, Precision, Recall and F1-score on testing data.100% accuracy is achieved by using the model Random Forest no misclassification on validation set.We have deployed the Resume Classification using Stream-lit as the platform
![image](https://user-images.githubusercontent.com/101926069/191781953-f3457f50-71a9-4dcc-96ca-590e4c171813.png)
![image](https://user-images.githubusercontent.com/101926069/191782011-8ef5b5de-86e4-44b4-9032-5c84f1593ee8.png)













