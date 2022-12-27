
This is the public dataset taken from the kaggle 

Link of the dataset: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

Findings :

- Data has 201 missing values in BMI column

- Checked average BMI for both men and women but there's not a much difference so filled all the missing null values in BMI columns with the overall average of both men and women together which is 28.89

- Seperated the dataset with the stroke status (where 0 - no stroke , 1 - stroke) to further analyze the data

- As we seperated the data with stroke status (0 and 1) We found that people who had stroke are relatively old peoples compared to the people who never had stroke, Also people who had stroke generally had high glucose level and body mass index

- People with private jobs are most affected with stroke in comparison with other type of jobs

- People from rural areas are least affected with stroke

- Surprisingly people who already have hyptertension suffered the stroke less as compared to the people who never had hypertension

- Similarly people who already have heart disease has suffered less stroke

- Susprisingly married people are the one who suffered mostly with stroke


After all the findinds, Build a decision tree model to predict if the person would suffer stroke or not
