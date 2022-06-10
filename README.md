# Stock-price-Prediction

This is a python program for stock price prediction of Adani Enterprises using Machine Learning.

This Program uses an artificial recurrent neural network called Long Short Term Memory(LSTM), to predict the closing stock price of Adani Enterprises using past 60 days data.

LSTM: Long-Short Term Memory based on Recurrent Neural Network(RNN).This recurring module(s) of 'tanh' layers in RNNs allow them to retain information. However,not for a long time, which is why we need LSTM Model.It is present in keras.layes module.

![image](https://user-images.githubusercontent.com/60754009/172042802-7457e9ff-c9b9-4dfa-b983-288cd4d7a3be.png)

The picture above depicts four neural network layers in yellow boxes, point wise operators in green circles, input in yellow circles and cell state in blue circles. An LSTM module has a cell state and three gates which provides them with the power to selectively learn, unlearn or retain information from each of the units.
<br>

Phase of the models:<br>
1.Getting and setting the data : We are using yfinance libary to import the data from the yahoo finance.<br><br>
![Screenshot_1](https://user-images.githubusercontent.com/60754009/172043158-6fc6c654-c591-4fb6-9f89-b3f5938f9399.png)

2.Ploting the data using matplot libary<br><br>
![Screenshot_2](https://user-images.githubusercontent.com/60754009/172043250-ac7f419e-dfa7-4fb0-9517-c063d9392602.png)

3.Making the train and testing dataset, and training the model.<br><br>
![Screenshot_5](https://user-images.githubusercontent.com/60754009/172043421-64bf1deb-14d3-4c4b-a3da-9700c4ee5667.png)

4.Predicting the price of the stock and ploting it.<br><br>
Here,<br>
->Blue Line: Is the data on which the model was trained.<br>
->Red Line: Is the original price on the certain day.<br>
->Orange Line: Is the model predicted value of the data.<br>
![Screenshot_3](https://user-images.githubusercontent.com/60754009/172043377-c706dafc-a1c4-4db7-832a-7b336ec15501.png)



