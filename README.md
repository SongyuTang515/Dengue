Dengue Fever Prediction
This project aims to predict dengue fever outbreaks using data-driven machine learning models. The goal is to assist public health officials in taking timely preventive measures.


📊 Data Description
raw/: Contains the original datasets as obtained from sources such as WHO, weather services, etc.

processed/: Contains cleaned and transformed datasets used for training and evaluation.

Typical data may include:

Weather information

Historical dengue case counts

Time features (year, month, etc.)

🧠 Model Overview
The model predicts future dengue case counts in specific regions. Major steps include:

Data cleaning and preprocessing

Feature engineering

Model training (e.g., Random Forest, XGBoost, LSTM)

Evaluation and model saving

Trained models are saved in the model/ directory.

🛠️ How to Use
Clone the repository

git clone https://github.com/SongyuTang515/Dengue.git
cd Dengue

Install dependencies

pip install -r requirements.txt

🧪 Evaluation Metrics
Common metrics used to evaluate model performance include:

MAE (Mean Absolute Error)
