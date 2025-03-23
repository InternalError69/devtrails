# Devtrails
hackathon code for guidewire devtrails.
We generate the dataset with the features such as pod_status and disk_usage and a target feature named "issue". (Refer the dataset in data folder).
Then we use a classifier called random forest to predict further data. (code for this is also provided in the python notebook)
The trained models were exported and also provided in the models folder.

To run the code with your own data set, simply replace the path for the "data" variable and run the code.
Ensure that the features in the replaced dataset are the same, if not then change the transformers.
