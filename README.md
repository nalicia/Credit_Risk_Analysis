# Credit_Risk_Analysis

## Overview
Credit Risk can be difficult to predict, so this week we used a few differenet models to train and evaluate classes. Using Imbalanced-learn and Scikit-learn libraries we built models using resampling.



## Results
Naive Random Oversampling
Our Balanced Accuracy Score was 65%, the recall score was okay coming in at 72% High-risk with the precision being 1%
<img width="826" alt="Screen Shot 2022-03-28 at 12 05 52 AM" src="https://user-images.githubusercontent.com/94723290/160324851-8291b559-1643-47a8-b900-8c33fa85d0eb.png">
<img width="806" alt="Screen Shot 2022-03-27 at 11 42 28 PM" src="https://user-images.githubusercontent.com/94723290/160324724-de5d481b-e5b5-4dc0-a03a-08ef9a1305ae.png">

Smote Oversampling
The balanced acuracy score was 66% The recall for the high risk was 63% with a precision of 1%
<img width="687" alt="Screen Shot 2022-03-27 at 11 43 03 PM" src="https://user-images.githubusercontent.com/94723290/160324734-19719d0a-03e9-44be-b883-208a54b982dd.png">
<img width="772" alt="Screen Shot 2022-03-27 at 11 43 08 PM" src="https://user-images.githubusercontent.com/94723290/160324736-33d423b0-fab2-4251-8d88-51771901371f.png">


Undersampling
The balanced accuracy score, like the Oversampling balanced accuracy score, was also 66%. The recall for High-risk was similar (63%) with 1% precision
<img width="722" alt="Screen Shot 2022-03-28 at 12 09 41 AM" src="https://user-images.githubusercontent.com/94723290/160325209-aab5efd7-8502-42bf-bc7b-f1c3db734db4.png">



Combination Over & Under Sampling
This sample algorithm is kind of like a combination between the last two and yields the same result.
<img width="599" alt="Screen Shot 2022-03-28 at 12 07 18 AM" src="https://user-images.githubusercontent.com/94723290/160325072-8db464ec-9dfe-408c-99ea-3d95b22a7013.png">



## Summary
This week we used several models to try to gett a deeper understandong of machiene learning and what goes into finding risk in a model. In the first models the accuracy score is relatvley low averaging about 65%. 
