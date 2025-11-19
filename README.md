# HOTEL DEMAND FORECASTING  
Accurate demand forecasting is essential for effective hotel revenue management. By anticipating booking trends, hotels can optimize pricing strategies, improve inventory allocation, and ultimately maximize profitability. 

This project analyzes booking data from three hotels (G, M, and W) between 2008 and 2010 to evaluate the forecasting performance of three different methodologies: Advance Booking (Pick-up) Model (additive and multiplicative), Feedforward Neural Network (FFNN), and Long Short-Term Memory (LSTM) model. The goal is to determine which approach provides the most accurate and reliable demand predictions

Since final demand varies between hotels, each model was trained separately for each hotel, and performance was evaluated using MAE, MAPE, and MASE to ensure a comprehensive comparison of accuracy. Hotel M has the most volatility, so it will likely have the least accurate predictions compared to other hotels 

Our results indicate that the FFNN model achieved the highest accuracy, followed by the Pick-up models, and then the LSTM model, with further analysis presented in the sections that follow 
