# Multilingual-Articles-Similarity-Evaluation
## CSV FILES 

- All the CSV files that are required are in the "CSV Files" folder.
- The file "input.csv" is the original dataset that is provided in the Semeval website.
- The file "realdata.csv" contains the text data for 1st and 2nd news articles of all the samples.
- This data is extracted from the json files provided to us and the dataset(folders containing json files) is assumed
   to be uploaded in the home directory of google drive.
- The file "hi1.csv" contains the encodings of 1st news articles of all the samples.
- The file "hi2.csv" contains the encodings of 2nd news artcles of all the samples.

## IMPLEMENTATION 

- There are three .ipynb files:
 	> Baseline mBERT model with Random Forest Classifier.<br>
 	> Improved mBERT model based on Gradient Boosting Regressor.<br>
 	> Final model based on DistilBERT with Random Forest Regressor.<br>
- The codeS ARE divided into 2 blocks.
1) Code for Data Extraction
	> This part contains the code corresponding to extracting and storing the data in a modular way.
2) Code for Model Implementation
	> This part contains implementation of model to obtain the similarity score.
- Most of the code is explained through comments
- All the external libraries that are required are included within the cells.
- If we are running this code on google colab uploading the dataset in google drive and the corresponding 
  CSV files in google colab should be sufficient for proper working of code.
- We also need to make sure that the path to dataset in google drive is properly set.




