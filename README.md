# FXCM_Stock_Price_Prediction

So this is the scenario, we had stock market information, from 1993 to 2018. And we want to use astrological coordinates and just that to predict the price of future dates, based on information we currently have. 

The model shows how to extract astrological coordaintes using DATES(using pyswisseph). And use them in LSTM model for predicting future prices. I've used a very small sample for model, as my client was insisting that we use only small data for training and use remaining samples to check if the pattern predicted (based on that small training data) was accurate enough.

I've used two LSTM model, one is multi-layered uni directional LSTM cells, and second model is of BI-directional multi-layered LSTM cells. 



