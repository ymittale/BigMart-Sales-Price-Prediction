# BigMart-Sales-Price-Prediction

Big Mart is One Stop Shopping center and Free Marketplace. The data scientists at Big Mart have collected 2013 sales data for 1559 products at 10 different stores in 
different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product
at a particular store. Using this model, Big Mart will try and understand the properties of products and stores which will play a key role in increasing sales. 
Our approach to the problem is very simple, we first understand the problem better by brainstorming possible factors that can impact the outcome. Then, we will look at
the categorical and continuous features and make some inferences about the data. Then we will check the dataset for some missing data i.e. the data pre-processing part.
Then, we move towards data fetching followed by importing features, splitting dataset, applying machine-learning algorithms, plotting the data points on map,
classification and finally prediction.

Data Pre-processing
The goal for this section is to take a glimpse on the data as well as any irregularities so that we can correct on the next section, Data Pre-processing.

	We checked whether the data has any missing values or not.
 

	Imputed missing values.
	







Feature Engineering
	Outlet_Establishment_Year besides being a hidden category, its values vary from 1985 to 2009 . It must be converted to how old the store is to better see the impact on sales.
 

	Modify the categories of Item_Fat_Content
 

Feature Transformation
	Categorical Variables — One Hot Encoding
Since scikit-learn only accepts numerical variables, we need to convert all categories of nominal variables into numeric types. So, we turn all categorical variables into numerical values using LabelEncoder() (Encode labels with value between 0 and n_classes-1). After that, we can use get_dummies to generate dummy variables from these numerical categorical variables

 



MODELING
Here in this project, for making predictions about the 2014 sales, we had used following Regression algorithms:
Linear Regression
Decision Tree Regression model 
Random Forest model 
Support Vector Regression

RESULTS
Linear Regression Model
 
Decision Tree Model
 
Random Forest Model 
Support Vector Regression
 

CONCLUSION
Here in this project, for making predictions about the 2014 sales, we had used various Regression algorithms Like Linear Regression, Decision Tree Regression model, Random Forest model and Support Vector Regression but we got the highest Accuracy of 82.95% , Cv_score of 40.89% and Lowest RMSE value of 704.54 with the Support Vector Regression.

