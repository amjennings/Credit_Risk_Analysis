# Credit_Risk_Analysis

## **Overview of the analysis:** 
###### The purpose of this analysis was to compare different techniques to train models to assess loan risk. Credit card data from a peer-to-peer lending service company, LendingClub, was used. The resampling techniques included oversampling, undersampling, and combined over- and undersampling. Ensemble classifiers included balanced random forest and easy ensemble classifier. 

## **Results**
######
- Naive Random Oversampling

<img width="309" alt="Screen Shot 2022-06-05 at 3 49 29 PM" src="https://user-images.githubusercontent.com/98051208/172067940-7766d9ec-8cf1-48ef-9704-6c0239fdf4e4.png">

<img width="638" alt="Screen Shot 2022-06-05 at 3 50 33 PM" src="https://user-images.githubusercontent.com/98051208/172067982-a40fc085-d35e-4cba-a192-fbb11bcf7391.png">

- SMOTE Oversampling

<img width="307" alt="Screen Shot 2022-06-05 at 3 53 19 PM" src="https://user-images.githubusercontent.com/98051208/172068087-05ac0154-a056-4e80-995f-a224739aafc6.png">

<img width="638" alt="Screen Shot 2022-06-05 at 3 51 40 PM" src="https://user-images.githubusercontent.com/98051208/172068027-247b25fb-c3a2-41c4-9c18-d317c47e7d97.png">

- Undersampling

<img width="307" alt="Screen Shot 2022-06-05 at 3 53 44 PM" src="https://user-images.githubusercontent.com/98051208/172068104-f96efa8e-d428-4dd9-ad12-3034c5fb32f7.png">

<img width="638" alt="Screen Shot 2022-06-05 at 3 51 07 PM" src="https://user-images.githubusercontent.com/98051208/172068008-cb7fe232-99f3-44dd-bce9-cb84b10b84c2.png">

- Combination

<img width="307" alt="Screen Shot 2022-06-05 at 3 54 05 PM" src="https://user-images.githubusercontent.com/98051208/172068115-1e93a0f6-62fe-4235-91fe-aa1e08a67fa3.png">

<img width="638" alt="Screen Shot 2022-06-05 at 3 52 42 PM" src="https://user-images.githubusercontent.com/98051208/172068063-d9764830-ba11-4ca3-a638-8d45b7fe2ca3.png">

- Random Forest

<img width="307" alt="Screen Shot 2022-06-05 at 3 55 15 PM" src="https://user-images.githubusercontent.com/98051208/172068161-60c08230-499e-4aae-bcd2-165893d33b8f.png">

<img width="646" alt="Screen Shot 2022-06-05 at 3 56 25 PM" src="https://user-images.githubusercontent.com/98051208/172068200-2fd9e62a-b7bc-43cd-b1b0-9ee9a16b4715.png">

- Easy Ensemble AdaBoost

<img width="307" alt="Screen Shot 2022-06-05 at 3 56 07 PM" src="https://user-images.githubusercontent.com/98051208/172068181-58628a37-961b-4508-b89d-dd742429e1b7.png">

<img width="646" alt="Screen Shot 2022-06-05 at 3 56 45 PM" src="https://user-images.githubusercontent.com/98051208/172068218-29084589-579e-40eb-94f8-fc5ee54adadf.png">


## **Summary**
###### TBD... Summary and recommendation of which model to use... Given the percentage of 5 star reviews are nearly equal for Vine and non-Vine members, there does not appear to be a positivity bias for paid reviews. An additional analysis of the average review rating across Vine and non-Vine members would be useful. Although the percentage of 5 star reviews may be roughly equal, there may be more 4, and even 3, star Vine reviews which could still indicate a positivity bias. Additionally, it would be useful to analyze reviews for other products aside from luggage.
