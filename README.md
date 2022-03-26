# Sales-Prediction
This project will be a sales prediction for food items sold at various stores. The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales.

Data Dictionary
Here is the Data Dictionary of this dataset:

Variable Name	                    Description
Item_Identifier	                  Unique product ID
Item_Weight	                      Weight of product
Item_Fat_Content	                Whether the product is low fat or regular
Item_Visibility	                  The percentage of total display area of all products in a store allocated to the particular product
Item_Type	                        The category to which the product belongs
Item_MRP	                        Maximum Retail Price (list price) of the product
Outlet_Identifier	                Unique store ID
Outlet_Establishment_Year	        The year in which store was established
Outlet_Size	                      The size of the store in terms of ground area covered
Outlet_Location_Type	            The type of area in which the store is located
Outlet_Type	                      Whether the outlet is a grocery store or some sort of supermarket
Item_Outlet_Sales	                Sales of the product in the particular store. This is the target variable to be predicted.

## Step 1: Data Cleaning
   
   Basic Data Cleaning is done, the process are:
  
   1. Deleting duplicates
   2. Identifying and Handling missing values
   3. Find and fix any inconsistent categories of data
   4. For any numerical columns, obtain the summary statistics of each (min, max, mean) to check for unusual values
   
## Step 2: Exploratory Data Analysis

  1. Create visualiztion on which product is mostly been bought at the stores.
   
   ![bar](https://user-images.githubusercontent.com/98469181/160244262-c35d74b3-e50b-443a-8f52-8b8044af57c9.JPG)

 2. Craeating Donut chart to show which are the Outlet Type and Outlet Location type has the most sales output.
    
    ![donut_1](https://user-images.githubusercontent.com/98469181/160244346-7e0ddfb6-4169-4c7b-b36f-ee682ae82503.JPG)
    ![donut_2](https://user-images.githubusercontent.com/98469181/160244374-87d7178d-629e-47b5-81c0-9816f3609f35.JPG)

   
 ## Step 3: Model Prediction
           
          For Machine Learning Models we tried 2 different models to test our Dataset and see which will provide the better result.
  1. Linear Regression Model
     from the score result, our dataset is not fit for this model due to high error on its test result.
   ![linear](https://github.com/ReaganTiburan/Sales-Prediction/blob/main/linear.JPG)

             
  2. Decision Tree Regression Model
     the result of this model is better than Linear Regression, we can see that the result of train and test score difference are small.
   ![tree](https://user-images.githubusercontent.com/98469181/160244649-8d06444f-088c-4f9f-a476-62ef96a6da7f.JPG)
   
   
      ## Recommendation:
      From the result of the two Models, we can recommend that the best Model for our dataset would be the Decision Tree Regression Model. It provides better score           result during our Model test.
 

          



    
    
    
