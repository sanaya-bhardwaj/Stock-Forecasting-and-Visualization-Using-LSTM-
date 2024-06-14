
# Stock Forecasting and Visualization Using LSTM

Predicting stock prices is difficult due to the market's volatility and complexity. Traditional methods like autoregressive models and moving averages often fall short in capturing stock price movements. *Long Short-Term Memory (LSTM) networks*, a type of deep learning model, have shown promise in better handling these challenges.

This project uses LSTM networks to forecast stock prices more accurately. Our approach includes:

**Data Preprocessing**: Cleaning and preparing historical stock data.

**Model Architecture**: Building LSTM networks for stock price prediction.

**Training and Evaluation**: Training the models and evaluating their performance.

**Visualization**: Visualizing historical data and prediction results.

**Baseline Comparison**: Comparing LSTM predictions with traditional methods.

Given real-time stock market data fetched from an API, the task is to develop an LSTM recurrent neural network model capable of effectively visualizing historical stock data and accurately forecasting future stock prices. It's aim is to provide better insights for investors, traders, and financial analysts to improve decision-making and risk management.


## System Requirements

**1. Programming Language**: Python

**2. Web Framework**: StreamLit

**3. Database**: MySQL

**4. API**: Yahoo Finance API

**5. ML Libraries**: Pandas, Numpy, Matplotlib, Scikit-learn

**6. ML Model**: LSTM


## Libraries/Modules for Data preprocessing, Model building, Training, and Evaluation.

- **`pandas`**: Used for data manipulation and analysis.
- **`MinMaxScaler`** from **`sklearn.preprocessing`**: Used to scale feature values to a range between 0 and 1, which is often beneficial for neural network models like LSTM.
- **`train_test_split`** from **`sklearn.model_selection`**: Used to split the dataset into training and testing sets.
- **`numpy`**: Used for numerical operations.
- **`tensorflow`**: Deep learning library for building and training neural networks.
- **`Sequential`** from **`tensorflow.keras.models`**: Used to create a sequential model, where layers are stacked sequentially.
- **`LSTM`** and **`Dense`** from **`tensorflow.keras.layers`**: Used to define the LSTM and fully connected (dense) layers in the neural network architecture.
- **`EarlyStopping`** from **`tensorflow.keras.callbacks`**: Used for early stopping during model training to prevent overfitting.
- **`matplotlib.pyplot`**: Used for data visualization, especially for plotting the model's performance metrics.
- **`mean_squared_error`**, **`mean_absolute_error`**, **`r2_score`** from **`sklearn.metrics`**: Used to evaluate the performance of the model.
##  Methodology Diagram
## Flow Chart
## Training & Testing 

TESTING: 20%
TRAINING: 80%

*Reason:*

1. **Balance between training and testing**: Allocating the majority of the data (80%) to training allows the model to learn from a sufficient amount of data, improving its ability to capture underlying patterns and relationships. Meanwhile, reserving a smaller portion (20%) for testing ensures that there is enough unseen data to evaluate the model's generalization performance accurately.

2. **Statistical significance**: A 80/20 split is often considered a good balance between having enough data for training and having enough data for testing to provide statistically significant evaluation results. While there is no strict rule for the split ratio, this division is commonly used and has been found to work well in practice.
## Conclusion

**LSTM Impact**:  Revolutionizes stock market predictions.

**Deep Learning Edge**:  Excels in pattern recognition, rooted in deep learning.

**Practical Benefits**: Aids traders and investors in managing market volatility.

**Effective Framework**: Demonstrates efficacy in visualization and forecasting.

**Decision-Making Advancement**: Represents a significant step forward for financial decision-makers.

**Integration Recommendation**: Suggests incorporating LSTM into existing methods.

**Risk Management Potential**: Holds promise for improved risk management in the stock market.

**Future Exploration**: Opens avenues for continued development at the intersection of deep learning and finance.