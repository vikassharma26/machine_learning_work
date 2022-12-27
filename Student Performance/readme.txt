This is a public dataset available on kaggle 

Link : https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

Findings :

- Data has no null values

- Making a new column 'Ranking' to provide student the rank based on their total marks, We will use this ranking feature for our machine learning model further

- Total Females - 512 , Males - 482

- Checked Male/Female ratio on the basis of race/ethnicity

- Checked test preperation course status based on the gender, Females have performed better 

- Checked gender based on ethnicity, Majority of the females are from 'Group C' whereas majority of the boys are from 'Group C and D'

- Checked lunch status based on the gender, Majority of the males and females were provided with 'standard' lunch

- Checked which group has performed better in overall marks, We found that group E has relatively performed better than others

- Checked gender wise which group has performed better in overall total marks, We found that in all the groups girls has relatively performed better

- Seperated male and female to further analyse based on gender

- Checked average math score of the students based on their parents education, We found that students whose parents have bachelor & masters's degree has relatively scored better

- Checked average reading score of the students based on their parents education, We found that students whose parents have masters's degree has relatively scored better

- Checked average writing score of the student based on their parents education, We found that students whose parents have masters's degree has relatively scored better

- Tried to check if anyhow parents education affect student preperation, We found that parents education has no direct relation with student's preparedness



Then finally build a machine learning model to predict how would student perform. Performance parameters are (0 - Excellent , 1 - Good , 2 - Poor)
