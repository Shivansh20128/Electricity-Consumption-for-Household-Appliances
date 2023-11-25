# ML_Project
This repository is for a course Project in Machine Learning

# Electricity Consumption For Household Appliances
In today’s world, increasing energy consumption and its
impact on the environment demand innovative solutions.
Traditional methods of tracking household electricity usage
lack granularity, failing to provide insights into specific appliance consumption patterns. This often leads to inefficient
energy utilization and higher bills. Our project aims to address these challenges through advanced machine-learning
techniques. By leveraging submeter readings and regression
models, we can accurately predict and categorize electricity consumption by individual appliances. This empowers
homeowners with precise insights, enabling them to optimize energy usage, reduce costs, and contribute to a more
sustainable future.

# Our goal
Our project aims to harness the power of diverse
machine-learning techniques to create an adept model for
predicting household electricity consumption. By employing submeter readings from distinct appliances, our model
endeavors to dissect energy usage patterns accurately, granting homeowners unprecedented insights into their consumption behaviors.


Upon culmination, we anticipate achieving a refined,
high-performing model that maximizes prediction accuracy
and provides a clear framework for identifying energy-hungry appliances and optimizing their usage. This outcome holds the potential to revolutionize energy management practices, offering individuals the means to curb
wasteful consumption, trim expenses, and contribute to a
greener environment. Furthermore, our model’s versatility extends its applications beyond households, finding utility in sectors such as smart grid management and energyefficient urban planning. Ultimately, this endeavor aspires
to empower individuals and communities to make informed
decisions, fostering a sustainable future, and mitigating the
the ecological footprint of electricity consumption.

# Dataset
Dataset details with data preprocessing techniques.
This dataset offers a valuable resource. It comprises six
months of electricity consumption records for a household,
spanning from January 2007 to June 2007. The dataset encompasses various metrics, including global active power,
global reactive power, voltage, and global intensity, as well
as sub-metering data for specific areas within the home,
such as the kitchen, laundry room, and electric water heater
and air conditioner. With a total of 260,640 measurements,
this dataset serves as a valuable tool for comprehending and
analyzing patterns in household electricity consumption.
![image](https://github.com/Shivansh20128/Electricity-Consumption-for-Household-Appliances/assets/88429611/c1b07430-9dbe-4fa2-a10e-7c569716b695)

# Methodology
Our main objective is to develop a predictive model for
predicting household electricity consumption by employing machine learning algorithms. In addressing the regression problem, we have explored different ML regression algorithms on the Dataset. 

**1. Data Preprocessing**

• Label Encoding

• Categorical Encoding

• One-Hot Encoding

• Feature Selection

• Target Variable

**2. Data Splitting**

In order to objectively assess the model’s performance,
the dataset was methodically partitioned into distinct
training and testing subsets. The training set comprised 80 percent of the data, serving as the foundation for model development, while the testing set constituted the remaining 20 percent, providing an independent dataset for rigorous model evaluation.

**3. Models**

(a) Linear Regression

(b) SGD (Stochastic Gradient Descent) Regression

(c) Ridge Regression

(d) Bayesian Regression

(e) Lasso Regression

(f) Decision Trees

(g) Random Forest Regressor

(h) MLP Regressor

(i) K Neighbours Regressor

**4. Model Evaluation**

The model’s performance was rigorously evaluated using three key metrics:

(a) Mean Squared Error (MSE)

(b) Root Mean Squared Error (RMSE)

(c) R-squared (R2) Score

**5. RESULT AND ANALYSIS**

After trying out all the regression models, we collected
results for all of them and compared them using established
metrics like MSE, RMSE, and R2 Score. Random Forest gave us
the best results.

![image](https://github.com/Shivansh20128/Electricity-Consumption-for-Household-Appliances/assets/88429611/cc790afb-febd-42ef-a770-080079c56684)

![image](https://github.com/Shivansh20128/Electricity-Consumption-for-Household-Appliances/assets/88429611/cd0ce565-244d-4f99-81c1-ed7465561d69)


