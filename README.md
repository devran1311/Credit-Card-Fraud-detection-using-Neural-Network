# Credit-Card-Fraud-detection-using-Neural-Network      
Credit card fraud detection using DNN algorithm         
The dataset is taken from Kaggle which contains European Credit Card transactions data        
The actual features of the Dataset is hidden for the sake of privacy and the columns are renamed as V1, V2....V28 using PCA     
The columns 'Time' and 'Amount' are left without any modification     
The column 'Class' shows whether the transaction details in the row contains the fraud or legitimate transaction.     
1 in Class column means Fraud and 0 means Legitimate transaction.
The dataset is highly imbalanced and there are only 492 rows of fraud data which is 0.027% of the total data.       
Thus the dataset is pre-processed and balanced. The variety of balancing techniques availble is SMOTE or ADASYN     
I have used a different apprach to balance the dataset, the balancing in my case is done manually by MS-Excel.
