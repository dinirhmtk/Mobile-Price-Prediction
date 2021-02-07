# Mobile Price Prediction 

<h4>Overview</h4>

Final project competition held by Sanbercode on Kaggle. This competition using datasets that already separated into train dataset and test dataset to predict mobile price range class with some conditions statement. The classification model that can determine value in the 'price_range' column by changing its value according to the following conditions below.
- 0 : 0-<1000k
- 1 : 1000k- <2000k
- 2 : 2000k-3000k
- 3 : >3000k

<h4>Data Description</h4>

There are 3 files used in this project, train.csv file contains a dataset that has label column used for model training, while the test.csv file contains a dataset without a label column which will be added a 'price_range' column containing mobile price prediction according to the condition previously mentioned. Then, create a new dataset containing the 'id' column and 'price_range' column taken from the test dataset that have added prediction to, this new dataset will be used as a submission file like the example of the submission in the submission_sample.csv file.

<h4>File Description</h4>

- train.csv : training dataset
- test.csv : test dataset
- submission_sample.csv : example of the submission file
