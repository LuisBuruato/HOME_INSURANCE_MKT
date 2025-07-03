
1.- BUSINESS UNDERSTANDING .
Using data mining tools I will be able to estimate  among 1003 customers which ones are  likely to buy a home insurance and which ones are not , based on 85 predictor variables that will be meaningful to take a right decision. Furthermore, I will be able to perform a Decision Cost/Benefit Analysis.  Firstly ,  I audited  the TRAINING DATA SET  of 8819 records to confirm that in fact there are 8819 records  and that they can be analyzed.

1.1.-The Data audit node gives me a general  vision about how my data behaves. For example : the home_insurance variable has more 0s than 1s , this tells me that most of the people rejected the home_insurance policy. We look this behavior in Figure 1.1

![Picture1](Desktop/HOME_INSURANCE_MKT/IMAGENES/Picture1.png)


ANALYSIS TRAINING DATA SET:  After analyzing the whole data set  I found out that there are not blanks and no missing values.


2 .- DATA UNDERSTANDING.
2.1.-Firstly,  using the statistics node I analyze the 85 predictor variables to find out the pearson  correlations  .Secondly  using the regression node I analyzed the first 43 predictor  variables which correspond to the same zip code  . Thirdly, I analyzed the predictor  variables from 44 to 85 using the regression node as well. Furthermore, using the CART algorithm  I analyzed the whole 85 variables. After analyzing each of the methods I decided to pick the best 5 variables from CART model. Table 2.1 shows this characteristic.

![Picture2](Desktop/HOME_INSURANCE_MKT/IMAGENES/Picture2.png)
