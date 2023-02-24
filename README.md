# loan_defaulter-eda-
datasets - https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter

## Insights from EDA
![image](https://user-images.githubusercontent.com/117656346/221157258-cc87e096-b389-4a7a-902f-1cb070901614.png)

-- most of the customers have taken cash loan

-- customers who have taken cash loans are less likely to default

![image](https://user-images.githubusercontent.com/117656346/221157603-c29156ba-d986-412e-8b92-9832042db9af.png)

### CODE_GENDER - 

most of the loans have been taken by female

default rate for females are just ~7% which is safer and lesser than male

![image](https://user-images.githubusercontent.com/117656346/221158012-11fbfc9f-a585-4176-a72e-33250bdeccbe.png)

### NAME_TYPE_SUITE - 

unacompanied people had tanken most of the loans and the default rate is ~8.5% which is still okay

![image](https://user-images.githubusercontent.com/117656346/221158673-b3cc2c2a-b1ab-47c6-9ea9-86196710050f.png)

### NAME_INCOME_TYPE - 

the safest segments are working, commercial associates and pensioners

![image](https://user-images.githubusercontent.com/117656346/221159267-62c85873-787d-4d64-9770-5c41dda57e2b.png)

### NAME_EDUCATION_TYPE - 
 
 Higher education is the safest segment to give the loan with a default rate of less than 5%
 
 ![image](https://user-images.githubusercontent.com/117656346/221159614-a35c05f1-e41b-4409-9eec-4ad47fa5465f.png)

### NAME_FAMILY_STATUS - 

Married people are safe to target, default rate is 8%

![image](https://user-images.githubusercontent.com/117656346/221159850-5e8416e7-7edd-4550-b6d5-51ef0b828fab.png)

### NAME_HOUSING_TYPE - 

People having house/appartment are safe to give the loan with default rate of ~8%
 
![image](https://user-images.githubusercontent.com/117656346/221161124-2da06522-169c-4216-8d76-caad5d154f87.png)
 
 ### OCCUPATION_TYPE - 

Low-Skill Laboreres and drivers are highest defaulters

Accountants are less defaulters

Core staff, Managers and Laborers are safer to target with a default rate of <= 7.5 to 10%

![image](https://user-images.githubusercontent.com/117656346/221161707-961830f0-9832-4f21-a0ec-f5d9f4885892.png)
![image](https://user-images.githubusercontent.com/117656346/221161792-564034d3-6aa9-4355-a188-07a01cb02baa.png)

### ORGANIZATION_TYPE - 
 
Transport type 3 highest defaulter

Others, Business Entity Type 3, Self Employed are good to go with default rate around 10 %
 
 
 ![image](https://user-images.githubusercontent.com/117656346/221164115-d255f567-71bb-403e-8b2f-861a79947d88.png)

## univariate numeric variables analysis

most of the loans were given for the goods price ranging between 0 to 1 millions

most of the loans were given for the credit amount of 0 to 1 millions

most of the customers are paying annuity of 0 to 50 K

mostly the customers have income between 0 to 1 millions

![image](https://user-images.githubusercontent.com/117656346/221164909-f8f039dc-156e-423f-8d79-85555c88cba9.png)

## bivariate analysis

AMT_CREDIT and AMT_GOODS_PRICE are linearly corelated, if the AMT_CREDIT increases the defaulters are decreasing

people having income less than or equals to 1 millions, are more like to take loans out of which who are taking loan of less than 1.5 millions, could turn out to be defaulters. we can target income below 1 million and loan maount greater than 1.5 million

people having children 1 to less than 4 are safer to give the loan

People who can pay the annuity of 100K are more like to get the loan and that's upto less than 2 millions (safer segment)


![image](https://user-images.githubusercontent.com/117656346/221165703-3b6791f1-8127-4dea-b643-56b90783fe73.png)
![image](https://user-images.githubusercontent.com/117656346/221165911-6627ddc6-418f-406d-8f08-5d45054d110a.png)

## analysis on merged data

for the repairing purpose customers had applied mostly previously and the same puspose has most number of cancelations

most of the application  which were previously either canceled or refused 80-90% of them are repayer in the current data

offers which were unused previously now have maximum number of defaulters despite of having high income band customers
 
 
# Final Conclusion

#### Bank should target the customers :-
 
having low income i.e. below 1 million
working in Others, Business Entity Type 3, Self Employed  org. type

working as Accountants, Core staff, Managers and Laborers 

having house/appartment and are married and having children not more than 4

Highly educated

preferably female
 
unacompanied people can be safer -  default rate is ~8.5%


#### Amount segment recommended 

the credit amount should not be more than 1 million

annuity can be made of 50K (depending on the eligibility)

income bracket could be below 1 million

80-90% of the customer who were previously canceled/refused, are repayers. Bank can do the analysis and can consider to give loan to these segments

 
 # precautions
 
 org. Transport type 3 should be avoide
 
Low-Skill Laboreres and drivers  should be avoided

offers previously unused and high income customer should be avoided
 
 
 
 
 
 
 
