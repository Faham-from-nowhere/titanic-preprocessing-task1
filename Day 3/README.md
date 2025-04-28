📄 Day 3: Linear Regression – Housing Price Prediction
🎯 Objective
Predict housing prices using linear regression models and optimize them through advanced techniques like regularization and hyperparameter tuning.

🛠️ Tools and Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📊 Steps Performed
Data Loading and Exploration

Feature Engineering

Outlier Detection and Removal (IQR method)

Feature Scaling (StandardScaler)

Model Building:

Simple Linear Regression

Multiple Linear Regression

Polynomial Regression

Ridge Regression

Lasso Regression

ElasticNet Regression

Hyperparameter Tuning (GridSearchCV for Ridge)

Model Evaluation using:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score (Coefficient of Determination)

📈 Model Comparison

Model	                             Techniques	                    R² Score	         MAE
Simple Linear Regression	      Area vs Price only	               ~	              ~
Multiple Linear Regression        All raw features	                 0.6529	           ₹970,043
Optimized Feature Regression	Only highly correlated features	     0.6226	           ₹1,029,010
Polynomial Regression 	           Non-linear features	             0.6216	           ₹1,032,367
Ridge Regression        	         Regularization	                 0.6682	           ₹785,110
Lasso Regression (Best Model)	Feature selection + regularization	 0.6684	           ₹784,877
ElasticNet Regression	           Hybrid Ridge + Lasso	             0.6636	           ₹790,611


🏆 Final Outcome
Best Model: Lasso Regression

Final R² Score: 0.6684

Final MAE: ₹784,877

The model predicts housing prices with reasonable accuracy after cleaning, scaling, and regularization.

