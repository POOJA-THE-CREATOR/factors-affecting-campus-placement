# factors-affecting-campus-placement
Engineering students start to experience placement pressure as their fourth year of study draws near. 
They constantly feel the need to hone their skills and assess where they fit within the group of students
graduating that year. The system's main objective is to help students perform better. In order to quickly 
find a respectable employment, students can then evaluate their strengths and flaws and take action to improve them.
Dataset used in the project was taken from Kaggle.
DATASET LINK: https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement

The formula below can be used to determine accuracy: 
Accuracy is equal to (TP+TN/TP+FN+FP+TN)100, where TP, TN, FN, and FP stand for the number of true positives, 
true negatives, false negatives, and false positive cases, respectively.

![image](https://user-images.githubusercontent.com/82519628/201527760-d5c5a213-7988-4b26-a5ea-0f64047cc75f.png)

Both from the institution's and the students' perspectives, the campus placement programme is crucial. To test these 
methods and raise student performance, a work has been examined and predicted using the classification algorithms SVC,
Random Forest, KNN and Gaussian Naive bayes. The model was developed using the following attributes and data set: 
manipulated by algorithms. Following analysis, the accuracy for SVC is 83.72%, for Random Forest it is 79.06%, for 
KNN it is 79.06% and for Gaussian Naive Bayes  it is 88.37%. In light of the analysis and prediction stated above, it 
is preferable to use the Gaussian Naive Bayes  method to predict the placement results.
From the EDA performed we came to the conclusion that  following features (Ignoring Board of Education -> they didnt 
seem to have much effect)are affecting student’s placement. 
 
Gender
Secondary Education percentage
Higher Secondary Education Percentage
Specialization in Higher Secondary Education
Undergraduate Degree Percentage
Under Graduation Degree Field
Work Experience
Employability test percentage
Specialization
MBA Percentage


