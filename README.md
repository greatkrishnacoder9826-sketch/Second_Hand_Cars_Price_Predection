Car Price Prediction Project
📌 Overview
This project predicts the selling price of used cars based on key features like manufacturing year, present price, and kilometers driven. It uses Linear Regression to build the prediction model and provides a Tkinter-based GUI for easy interaction.

🚀 Features
✅ Data preprocessing (handling duplicates, encoding categorical variables)

✅ Linear Regression model training

✅ Model evaluation using R² Score

✅ Interactive GUI for price prediction

✅ User-friendly input interface

📊 Dataset
The dataset contains information about used cars including:

Car_Name - Name of the car

Year - Manufacturing year

Selling_Price - Target variable (price in Lakhs)

Present_Price - Current showroom price (in Lakhs)

Kms_Driven - Kilometers driven

Fuel_Type - Petrol/Diesel/CNG

Seller_Type - Dealer/Individual

Transmission - Manual/Automatic

Owner - Number of previous owners

🛠️ Technologies Used
Library	Purpose
Pandas	Data manipulation
NumPy	Numerical operations
Scikit-learn	Model training & evaluation
Tkinter	GUI development
PIL	Image handling
📈 Model Performance
Algorithm: Linear Regression

R² Score: ~84.7%

Features used: Year, Present_Price, Kms_Driven

🖥️ How to Run
Prerequisites
bash
pip install pandas numpy scikit-learn pillow
Steps
Clone the repository

bash
git clone https://github.com/yourusername/car-price-prediction.git
cd car-price-prediction
Run the Jupyter notebook to train the model

bash
jupyter notebook 1.ipynb
Run the GUI application

bash
python gui_app.py
📁 Project Structure
text
car-price-prediction/
│
├── 1.ipynb                 # Model training & EDA notebook
├── 2.ipynb                 # GUI application notebook
├── car_prediction_data.csv # Dataset file
├── README.md               # Project documentation
└── background.png          # GUI background image (optional)
🖼️ GUI Preview
The GUI accepts three inputs:

Car Model Year (e.g., 2015)

Car Original Price (in Lakhs)

Kilometers Driven (e.g., 50000)

Click "Predict Price" to get the estimated selling price.

📝 How Prediction Works
Data is loaded and cleaned (removing duplicates)

Fuel_Type is encoded using LabelEncoder

Only numerical columns are selected for training

Linear Regression model is trained on Year, Present_Price, Kms_Driven

Model predicts Selling_Price based on user inputs

🧪 Sample Prediction
Input	Value
Year	2017
Present Price	9.85 Lakh
Kms Driven	69,000
Predicted Selling Price	~7.44 Lakh
🔮 Future Improvements
Add more features (Fuel Type, Transmission, Owner count)

Try advanced algorithms (Random Forest, XGBoost)

Add data visualization in GUI

Deploy as a web application using Flask/Streamlit

👨‍💻 Author
Krishna Great