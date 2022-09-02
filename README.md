# Amazon_Vine_Analysis

## Overview of the analysis: 
The purpose of this review is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.

## Results: 
Below are the DataFrames that were transformed from our dataset from Amazon Review datasets:

![image](https://user-images.githubusercontent.com/104603037/188052018-f6c337c7-ab00-4f48-b1ec-716c34ffb803.png)

![image](https://user-images.githubusercontent.com/104603037/188052048-3de192f3-9821-414c-8662-ed500c4dfcbe.png)

![image](https://user-images.githubusercontent.com/104603037/188052065-f104b6b3-e316-4c85-b254-0ec55a5c3426.png)

![image](https://user-images.githubusercontent.com/104603037/188052091-79cb8203-0e07-4161-ac7d-0806c9abd40b.png)


Below are the dataframes for the four Tables uploaded on PGAdmin from our Analysis

- review_id_table:

![image](https://user-images.githubusercontent.com/104603037/188048669-48f9ba32-e44f-483f-8b3b-537969989988.png)

- product table:

![image](https://user-images.githubusercontent.com/104603037/188048586-5ffa8cac-73f4-4544-b967-7bbfe4b9a2f5.png)

- customer table:

![image](https://user-images.githubusercontent.com/104603037/188048617-7856d50d-290d-4ee0-a93c-80c7820cd0b3.png)

- vine table:

![image](https://user-images.githubusercontent.com/104603037/188048636-84be5c89-68b7-467b-bef1-8243a681cd2e.png)


- Paid Vine Dataframe

![image](https://user-images.githubusercontent.com/104603037/188050885-0f50f6ed-cc87-4692-a69c-47912e28ff2d.png)

- Unpaid Vine Dataframe

![image](https://user-images.githubusercontent.com/104603037/188050937-4d6a863f-5c58-4e4a-a774-da4b84c74eeb.png)

There were 33 Vine reviews and  and 45388 non-Vine reviews
![image](https://user-images.githubusercontent.com/104603037/188050436-1e682b5a-75b6-4c6f-8b42-c0f6e4ad3b9a.png)

- There were 15 Vine reviews that were 5 stars and 23733 non-Vine reviews that were 5 stars
![image](https://user-images.githubusercontent.com/104603037/188054704-1b651d32-e731-4d0d-8496-68fc37172448.png)

- 0.000452% percentage of Vine reviews of the total 5 stars reviews while 0.714729% percentage of non-Vine reviews of the total 5 stars reviews
![image](https://user-images.githubusercontent.com/104603037/188054651-0fef8fff-2d87-41d2-86ee-bfd04816ae6d.png)

## Summary:

- From the above analysis we can deduce that there is bias for reviews in the Vine program considering the fact that the paid review is very low when compared with unpaid Vine reviews for overall reviews and 5 rating reviews. 

Additional analysis:
- We can perform average rating within a period of time using column review_date to know the trend when we have the five rating mostly.
