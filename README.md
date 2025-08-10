## Stock Trend Prediction

This project is a stock trend prediction application that uses a **Long Short-Term Memory (LSTM)** neural network. The application is built with Streamlit, making it a user-friendly, interactive web tool.

### Features

  * **Data Retrieval**: Downloads historical stock data from Yahoo Finance for any given stock ticker.
  * **Model Training**: Uses an LSTM model, a type of recurrent neural network well-suited for time-series forecasting, to learn patterns from the historical data.
  * **Data Visualization**: Generates plots to visualize the original stock price, the predicted price, and the overall trend.
  * **Interactive Interface**: A simple Streamlit user interface allows users to input stock tickers and view the predictions.

### Technologies Used

  * **Streamlit**: For creating the interactive web application.
  * **Python**: The core programming language.
  * **Pandas & NumPy**: For data manipulation and numerical operations.
  * **yfinance**: For downloading stock data from Yahoo Finance.
  * **Scikit-learn**: For data preprocessing (e.g., scaling with `MinMaxScaler`).
  * **Keras & TensorFlow**: For building and training the LSTM deep learning model.
  * **Matplotlib**: For plotting and visualizing the data.

### Installation

To run this project locally, follow these steps:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Kousik1314/Stock_Trend_Prediction.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd Stock_Trend_Prediction
    ```

3.  **Install the required libraries:**

    ```bash
    pip install streamlit pandas numpy yfinance
    ```

### How to Run the App

1.  After installation, ensure you have a Python file (e.g., `app.py`) containing the Streamlit code.

2.  Run the application from your terminal:

    ```bash
    streamlit run app.py
    ```

3.  Your web browser will automatically open a new tab with the running application. You can now interact with the stock trend predictor.

### File Structure

  * `app.py`: The main Streamlit application file.
  * `LSTM_MODEL.ipynb`: The Jupyter Notebook containing the model building and training code.