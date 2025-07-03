
1.- BUSINESS UNDERSTANDING .
Using data mining tools I will be able to estimate  among 1003 customers which ones are  likely to buy a home insurance and which ones are not , based on 85 predictor variables that will be meaningful to take a right decision. Furthermore, I will be able to perform a Decision Cost/Benefit Analysis.  Firstly ,  I audited  the TRAINING DATA SET  of 8819 records to confirm that in fact there are 8819 records  and that they can be analyzed.

1.1.-The Data audit node gives me a general  vision about how my data behaves. For example : the home_insurance variable has more 0s than 1s , this tells me that most of the people rejected the home_insurance policy. We look this behavior in Figure 1.1

![Picture1](Desktop/HOME_INSURANCE_MKT/IMAGENES/Picture1.png)


ANALYSIS TRAINING DATA SET:  After analyzing the whole data set  I found out that there are not blanks and no missing values.


2 .- DATA UNDERSTANDING.
2.1.-Firstly,  using the statistics node I analyze the 85 predictor variables to find out the pearson  correlations  .Secondly  using the regression node I analyzed the first 43 predictor  variables which correspond to the same zip code  . Thirdly, I analyzed the predictor  variables from 44 to 85 using the regression node as well. Furthermore, using the CART algorithm  I analyzed the whole 85 variables. After analyzing each of the methods I decided to pick the best 5 variables from CART model. Table 2.1 shows this characteristic.

![Picture2](Desktop/HOME_INSURANCE_MKT/IMAGENES/Picture2.png)

As we can see on Figure 2.1  :    “Cont_car_pol”   ( contribution car policies )  has the highest predictor importance nevertheless the other  predictors have a considerable importance as well. 

![Picture3](Desktop/HOME_INSURANCE_MKT/IMAGENES/Picture3.png) 

2.2.-Among  the  predictor variables ,   I found that the subtype variable (customer subtype) has 41 segmentation categories which give some interesting  information  as we can see  on figure 2.2.1 
Main categories:
1st  Category: Lower class large families:  14.17% (1250)
2nd Category: Traditional  families:  5.89% (519)
3rd Category: Middle class families: 5.67 % (500)

![Picture4](Desktop/HOME_INSURANCE_MKT/IMAGENES/Picture4.png) 

Conclusion:  This analysis  tell me that most of the customers  in the Data Training set belong to large families that are middle-lower traditional families but families represent the principal customers  of the data set.

2.3.- To emphasize the above conclusion and using the distribution node  I analyzed the  cust_type  variable (customer main type)  and gives me the some other good information about families as main customers. Figure 2.3.1 .  This variable has 10 segmentation categories and I chose the 3 most important :
1st Category: Family with grown ups: 27.3% : 2408
2nd Category: Average family: 15.24%: 1344
3rd Category: Conservative families : 11.51%: 1015

![Picture5](Desktop/HOME_INSURANCE_MKT/IMAGENES/Picture5.png)

    I concluded that indeed  the main customers   for a mobile home insurance would be  families with  grown ups: average families and conservatives which share very similar characteristics as point 2.2. I assume  that the main customers would be traditional U.S families with an average income to buy a car policy. However, further analysis will be performed.

































