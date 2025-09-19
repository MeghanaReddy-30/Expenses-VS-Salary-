# Healthcare Insurance Expenses 
My first GitHub Repository 
<br>
Author - Meghana Reddy 
# Insurance Charges Prediction (Using Age, Sex, BMI, Children)

This project uses the **Insurance dataset** to predict medical insurance charges.  
We apply a simple **Linear Regression model** using only the following features:  

- Age  
- Sex  
- BMI  
- Children  

## Dataset
[Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)  

## Project Workflow
1. **Data Preprocessing**  
   - Selected columns: age, sex, bmi, children, charges  
   - Encoded categorical variable: `sex` (male=1, female=0)  

2. **Model Training**  
   - Split data into training and testing sets  
   - Trained a **Linear Regression model**  

3. **Evaluation**  
   - Calculated **Mean Squared Error (MSE)**  
   - Calculated **R² Score**  
   - Plotted Actual vs Predicted charges  

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Insurance-Charges-Prediction.git
   cd Insurance-Charges-Prediction
