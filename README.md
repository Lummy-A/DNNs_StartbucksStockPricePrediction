# Building Deep Neural Networks for Starbucks Stock Open Price Prediction
In this project, we leveraged 4 Deep Neural Networks (DNNs) to predict the daily opening stock price of Starbucks. We used 2 well known existing DNNs, and built 2 Hybrid DNNs. By utilizing historical stock price data from 2017 to 2025, we aim to provide accurate stock price predictions to support financial analysis and decision-making.

## Introduction

Predicting stock prices is a challenging task due to the dynamic and complex nature of financial markets. In this project we built, hypertuned, and trained 4 Deep Neural Networks (DNNs) to predict Starbucks' daily opening stock prices using a historical Starbucks dataset. We employed data preprocessing techniques, model optimization, and performance evaluation to achieve the best possible predictions. We aimed to address the task in 3 different ways. In the code file, the first model processes the data independently at each time instance, the second and third models process the data as a timeseries, and the fourth deep network approaches the task as a regression problem. 

- **Model 1: FNN (FeedForward Neural Network)**
- **Model 2: Long Short-Term Memory (LSTM)**
- **Model 3: Attention-GRU**
- **Model 4: Hybrid CNN-BiLSTM-Attention DNN**

## Project Workflow

The workflow of this project is as follows:

1. **Data Loading and Exploration**:
   - Loaded and inspected historical stock price data from 2017 to 2025.
   - Performed extensive exploratory data analysis (EDA) to understand the dataset's structure and distribution.

2. **Data Preprocessing**:
   - Cleaned and preprocessed the data by handling missing values and scaling numerical features.
   - Carried out feature engineering
   - Split the dataset into training, validation, and testing sets.

3. **Model Building**:
   - Designed and implemented 4 Deep Neural Networks (DNNs) with TensorFlow/Keras.
   - Carried out hyperparameter tuning to optimize the model's performance.

4. **Model Training and Evaluation**:
   - Trained the untuned and tuned DNNs using the preprocessed dataset.
   - Evaluated the model's performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²).
   - Visualised the training and validation loss

5. **Results Visualization**:
   - Visualized the model's predictions compared to the actual stock prices.
   - Generated plots to interpret the model's accuracy and performance.

---
##  How To Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Lummy-A/DNNs_StarbucksStockPricePrediction.git
   cd Building_DNNs_for_Starbucks_Open_StockPrice_Prediction.ipynb
2. Navigate into the project directory:
   ```bash
   cd Building_DNNs_for_Starbucks_Open_StockPrice_Prediction.ipynb
3. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
4. Install the required dependencies: Install all the Python libraries listed in the requirements.txt file by running:
   ```bash
   pip install -r requirements.txt
5. Open the Jupyter notebook: Launch Jupyter Notebook to open the project:
   ```bash
   jupyter notebook group_notebook.ipynb
6. Run the notebook:
   Once the notebook opens, run the cells in order to load the data, train the models, and evaluate them.
   The results, including metrics and plots, will appear as you go through the notebook.

**For running in Google Colab (Optional):**
If you prefer not to run it locally and want to try it on Google Colab, just follow these steps:
1. Open Google Colab.
2. Click on File → Open notebook.
3. Select the GitHub tab and enter your repository URL:
https://github.com/Lummy-A/DNNs_StarbucksStockPricePrediction
4. Open the notebook from the list and run it just like you would in Jupyter Notebook.

## Collaborators
This project is a collaboration between
- **Lum Apeh Temukum**
- **Devashish Vidhate**
- **Kaushik Kumar** 
- **Sai Priyadharsini**

## Contributing

We welcome contributions! If you’d like to help improve this project, follow these steps:

1. Fork this repository.
2. Clone your fork locally.
3. Create a new branch (`git checkout -b feature-branch`).
4. Make your changes and commit (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

Feel free to open an issue for any questions, suggestions, or bugs!

## References
This project cites academic papers and textbook references for the DNNs, evaluation technique, and model improvement strategies.
(Full reference list is included inside the project folder.)

## Acknowledgement
Generative AI (ChatGPT) was used for code optimization suggestions.
All main logic, model building, evaluation, and tuning were manually implemented.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

