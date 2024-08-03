---
title: "A Method for Predicting Real-Time Carriage-Level Alighting Flow Based on Train Weighing Data by Incorporating Correlations Among Carriages"
collection: publications
date: 2024-05-02
permalink: /publications/carriage
excerpt: >
  The dynamics and randomness of boarding and alighting flow usually lead to unbalanced congestion across multiple carriages of one metro train. Train weighing sensors make it possible to acknowledge each carriage’s weights in real-time, but it is still hard to know the alighting passengers at the next station, making it difficult to organize boarding flow in advance to balance each carriage’s congestion. Moreover, the correlations among multiple carriages strengthen the complexity of alighting flow prediction. This study will adopt the Convolutional Long-Short Term Memory (convLSTM) model based on the multichannel features to predict the carriage alighting flow with the consideration of correlations among carriages. Firstly, the historical carriages’ alighting flow is extracted by monitoring the variations of weights caused by the passengers getting on/off carriages based on the train weighing sensors. Then, the convolution operations are used to extract the correlation between carriages in spatial dimensions. Finally, the LSTM model captures the temporal correlations among carriages and predicts the alighting flow of each carriage. Based on the train weighing data, the model is applied and specified in Guangzhou Metro Line 14 where one metro train consists of 6 carriages. The results show that the proposed model has better performance than other deep learning methods and the model that considers the adjacent carriages’ correlations performs best.<br/><img src='/images/graph.png'>
  <br/><img src='/images/model.png'>
---
