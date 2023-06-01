# TexasSalaryPrediction_and_EDA

# Attribute Information :

Agency Agency Name Last Name First Name MI (Middle Initial) Class title Ethnicity Gender Status Employ Date Hourly rate Hrs per week Monthly (Monthly income) Annual (Annual Income) State number

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model which will help theTexas state government team to know the payroll information of employees of the state of Texas.

Task 3:-

● Who are the outliers in the salaries?

Used below model to test the data set
from sklearn.tree import DecisionTreeRegressor,ExtraTreeRegressor
from sklearn.neighbors import KNeighborsRegressor
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import GridSearchCV
from sklearn.linear_model import Lasso, Ridge, ElasticNet
from sklearn.ensemble import GradientBoostingRegressor,AdaBoostRegressor,RandomForestRegressor
from sklearn.linear_model import LinearRegression
from sklearn.svm import SVR
from sklearn.metrics import mean_absolute_error 
from sklearn.metrics import mean_squared_error 
from sklearn.metrics import median_absolute_error,r2_score
from sklearn.model_selection import GridSearchCV,RandomizedSearchCV
