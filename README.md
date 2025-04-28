# Linear Regression Model on Housing Dataset

This project implements a **Linear Regression** model using the **Housing.csv** dataset to predict housing prices based on multiple features.

## 📂 Dataset
- **Filename:** `Housing.csv`
- **Description:** The dataset contains various features that can affect housing prices, such as:
  - Area
  - Number of bedrooms
  - Number of bathrooms
  - Stories
  - Main road access
  - Guest room availability
  - Basement availability
  - Hot water heating
  - Air conditioning
  - Parking spaces
  - Furnishing status
  - And more.

## 🚀 Project Structure

├── Housing.csv # Dataset 
├── model.py # Code to train the Linear Regression model 
├── requirements.txt # Python package dependencies 
└── README.md # Project documentation

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/linear-regression-housing.git
   cd linear-regression-housing
2.Install dependencies

pip install -r requirements.txt

3.Run the model training script

python model.py


📈 Model Workflow
Load the dataset

Preprocess the data (handle categorical features, missing values if any)

Split the dataset into training and testing sets

Train the Linear Regression model

Evaluate the model using metrics like R² Score and Mean Squared Error

📊 Example Outputs
R² Score (Train Set): 0.87

R² Score (Test Set): 0.84

(Example scores — your results may vary.)

🧩 Technologies Used
Python 3.10+

Pandas

NumPy

scikit-learn

matplotlib (for visualization)

📝 Requirements
Create a requirements.txt file with the following content:
pandas
numpy
scikit-learn
matplotlib

