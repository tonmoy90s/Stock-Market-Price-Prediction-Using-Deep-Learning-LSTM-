Course Code: CSE 460 | Course Title: Deep Learning Lab

Submitted by: Tonmoy Talukder (ID: 0562210005101019)

Supervised by: Razorshi Prozzwal Talukder, Lecturer

Institution: Department of Computer Science and Engineering, North East University Bangladesh

🎥 Project Video (Google Drive): https://drive.google.com/file/d/17rygV073_wrouIkAuMBenRzuTzImiwvW/view?usp=sharing

🌐 Live Web Application: https://p4soguy4t8tog6ibnqqply.streamlit.app/

📊 Project Dataset : Download from yfinance

📄 Final Project Report (Google Drive): https://drive.google.com/file/d/1X9xNFzZhhQk1GZe65OfVy9cQBgBaMlGP/view?usp=sharing

📄 Project Proposal (Google Drive): https://docs.google.com/document/d/1-7os9NKAC2Y2dU-dx8ng4qfM77SgLFerH2ynE5HUr5c/edit?usp=sharing



# Stock Market Price Prediction Using LSTM

## About the Project

This project was developed to predict the future closing price of Google (GOOG) stock using a Long Short-Term Memory (LSTM) model. The main goal of the project is to understand how deep learning can be applied to stock market prediction by using historical stock price data.

The historical data was collected from Yahoo Finance using the **yfinance** library. After preprocessing the data, an LSTM model was trained to predict the next day's closing price.

---

## Dataset

The dataset contains the historical stock prices of Google (GOOG) for the last five years.

**Dataset Source:** Yahoo Finance

The dataset includes the following information:

* Open Price
* High Price
* Low Price
* Close Price
* Volume

For this project, only the **Close Price** was used for training the model.

---

## Tools and Libraries

The project was developed using the following tools and libraries:

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* yfinance
* Streamlit

---

## Project Workflow

The project follows these steps:

1. Download stock price data from Yahoo Finance.
2. Check and preprocess the dataset.
3. Normalize the closing price using Min-Max Scaling.
4. Create sequences of the previous 100 days.
5. Train the LSTM model.
6. Predict the future closing price.
7. Compare the predicted price with the actual price.
8. Evaluate the model using RMSE.

---

## Result

The model was able to predict the overall trend of Google's stock price. Although the predicted values were not exactly the same as the actual prices, they followed the market trend reasonably well.

The RMSE obtained during the experiment was around **13.13**. Since the data is downloaded directly from Yahoo Finance, the result may change slightly when the model is trained again with updated data.

---

## How to Run

1. Download or clone this repository.
2. Install the required Python libraries.
3. Open the project folder in VS Code.
4. Run the following command:

```bash
streamlit run web_stock_price_predictor.py
```

5. The application will open in your browser.

---

## Future Work

In the future, this project can be improved by:

* Using more input features such as Open, High, Low, and Volume.
* Adding technical indicators like RSI and MACD.
* Comparing the performance of LSTM with GRU, Bidirectional LSTM, and CNN-LSTM.
* Improving the model through hyperparameter tuning.

---

## Author

**Tonmoy Talukder**

Department of Computer Science and Engineering (CSE)

North East University Bangladesh
