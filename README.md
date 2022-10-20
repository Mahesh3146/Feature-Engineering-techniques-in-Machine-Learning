# Different types of feature engineering techniques in Machine Learning Algorithms

Feature Engineering :
  * It is process of using a domain data to create features that makes machine learning algorithms works best.
  * If feature engineering works acccuratly then it increases the predictive power of the ML algorithms.

## 1 . Feature Scaling :
        # It is tranforms all of the features of  data into within  same ranges is called  feature scaling.
        # Feature scaling applied where distance matric are used at that point we are using scaling technique used.
        
        There are two types of scaling techniques are there :
          
            * Standard Scaler
            
                1 . Standard Scaler takes our data and makes it into  Normal Distribution ( mean = 0 , Standard Deviation = 1 ).
                2 . Standard Scaler is applied when our dataset contains outliers.
                
                              Z = (X - U ) / S
                          
                          where 
                                Z = scaled data
                                X = data 
                                U = mean of training data
                                S = standard deviation of training data
                          
              
            * MinMax Scaler
            
                1 .  Min Max scaler scales our features into predefined range ( 0 - 1  range ). It makes into Statistical Distribution.
                2 . It uses the minimum and maximum values of each feature in our dataset .
                
                             x_std = ( x - x.min ) /  ( x.max - x.min )
                             
                             x_scaled = x_std *( max - min ) + min 
                             
                             where 
                                   x = data
                                   x.min = minimum value feature
                                   x.max = maximum values of feature
                                   max = maximum range of feature
                                   min = minimum range of feature
                                   x_scaled = scaled data
                                   
                
            
              
