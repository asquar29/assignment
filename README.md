Firstly, we have imported all necessary libarires.
Then,we check all Null values 
since, cabin has 687 null values out of 891. so, we remove the column. 
we have replaced the 'Age' column null value with its median value. 
similarly,with 'Embarked'
And we don't require Name and Ticket. SO, we have drop that columns.

We checked how many categoreies have numerical and categorical feature. 
then we converted 'Sex' and 'Embarked' categorical into numerical using OneHotEncoder and column Transformation.

After that we checked tha outliers using boxplot and reomved it using IQR method.

then use standardize the data using StandardScaler.
