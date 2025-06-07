# Practical-Application-2

**Problem Statement:** What drives the price of a used car?

Background: There are many factors that influences the used car price. We need to provide the insights to the group of used car dealerships on what drives the used car price so they can strategize their inventory and business.

Business Objectives: Identify top factors that drives used car price.

Business Success Criteria:
Identify the ideal regression model to run on test data and confirm the predictions are as expected with least error.

Technical Resources Used:
- Tools and Techniques: Used car dataset - Vehicles.csv.
- Regression models: Linear regression model, Ridge regression model, Lasso regression model,
- Cross validation techniques: Grid Search CV
- Error metrics: Mean squared error, Root mean squared error, Mean absolute error, R2 score
- Fine tuning regression algorithm techniques - Polynomial features, Standard Scaler, Sequential feature selection, JamesSteinEncoder  

Data task: This problem is worked as supervised machine learning problem. Using the Vehicles.csv data, the goal is to use multiple regression models to predict the factors that drives the used car price. In the dataset provided we will use price column as dependent variable and other columns contributing to the price of car as independent variables.

**Summary Of Findings:**

The following features affects the price of the used car the most. Used car dealers should consider these suggestions while fine-tuning the used cars inventory.
* Year: Year by itself has strong impact on the price of the car which makes sense as newer the car the higher the price.
* Year, model and state: These three features in combination drives the price of a car, i.e. along with Year the buyer will be looking at model and associated state( more for the buyers buying a car other than the state he/she lives.)
* Region, fuel and title status: These three features in combination affects the price of a car. Depending upon the region, particular fuel type car would be more in demand accompanied by the title status.
* Cylinder, drive and type: These three features affects the price of a car so having inventory to have correct combination of cylinder, drive and type of for used cars will help drive the price higher.
* Model: Model of the care is very important to consider which drives the used car price.
* Year: Year is another important feature that drives the car price.
* Region: Region is very important while considering higher price for the used car (more for the buyers buying a car having state other than the state he/she lives).
* Type: Type of the car whether it is a SUV, hatchback, pickup, sedan etc. will affect the car price significantly.
* Drive: Different drive types like 4WD, 2WD etc. will directly affect the price of the used car
* Odometer: The value of the Odometer affects the car price. The lower the odometer value the higher the price.

**Next steps and recommendation**
* Fine tune the inventory taking in consideration of the above listed features that most influences the used car price.
  

**Link to notebook:**  
