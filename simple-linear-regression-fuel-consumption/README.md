📘 Simple Linear Regression — Fuel Consumption & CO₂ Emissions
This project implements a simple linear regression model using Python and scikit‑learn to predict vehicle CO₂ emissions based on engine size and fuel consumption data.

It demonstrates a complete machine learning workflow:
data loading → exploration → visualization → model training → evaluation.

🚗 Dataset
Source: Government of Canada
Dataset: FuelConsumptionCo2.csv

It contains detailed information about light‑duty vehicles sold in Canada, including:

Model year

Make and model

Vehicle class

Engine size (ENGINESIZE)

Number of cylinders

Fuel consumption (city, highway, combined)

CO₂ emissions (g/km)

This dataset is ideal for practicing regression due to its clear linear relationships.

🎯 Project Objectives
Implement simple linear regression using scikit‑learn

Visualize relationships between features and emissions

Train a model to predict CO₂ emissions

Evaluate performance using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

🧠 Technologies Used
Python 3

NumPy

Pandas

Matplotlib

Scikit‑learn

Jupyter Notebook / VS Code

📊 Key Results
The model using ENGINESIZE shows a clear linear trend but moderate variance.

The model using FUELCONSUMPTION_COMB achieves a lower MSE, indicating better predictive performance.

Visualizations confirm that combined fuel consumption is a stronger predictor of emissions than engine size alone.

📁 Repository Structure
Código
simple-linear-regression-fuel-consumption/
│
├── Simple-Linear-Regression.ipynb   # Main notebook
├── regression_plot.png              # Model visualization (optional)
└── README.md                        # Project documentation
🚀 How to Run the Project
Install dependencies:

bash
pip install numpy pandas scikit-learn matplotlib
Open the notebook in Jupyter or VS Code.

Run all cells to reproduce the analysis and visualizations.

🧩 Possible Improvements
Add multiple linear regression with more features

Compare models (LinearRegression vs Ridge vs Lasso)

Add cross‑validation

Build an interactive dashboard with Streamlit

👤 Author
Project created by Oscar, as part of a machine learning learning path. **IBM AI Engineering**
