# Home Energy Prediction

This is a project I worked on to learn about predicting home energy consumption using time-series models such as GRU. The goal was to build a predictive model from scratch, focusing on understanding how to preprocess data, create a custom AI model, and train it effectively. I did not use pre-trained models, which did affect my accuracy, but the goal of this project was to design the architecture myself to gain deeper insights into how these systems work.

The data for this project was collected directly from my own house over the span of one year. Due to the limited amount of data, the model's accuracy is not perfect and it struggles to capture long-term trends. However, the process provided valuable experience in building and training machine learning models on unstructured data.

The purpose of this project was educational, so the accuracy is limited, but the experience gained was valuable.

![energy_usage](https://github.com/user-attachments/assets/cd8238f7-68ac-4a61-b1c8-ed117ab32496)

## How to Use
   ```bash
   git clone https://github.com/DeadEvilV/HomeEnergyPrediction.git
   cd HomeEnergyPrediction
   pip install -r requirements.txt
   python src/main.py --predict
   ```
