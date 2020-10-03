# the_depths
![Deep Learning](https://fedtechmagazine.com/sites/fedtechmagazine.com/files/styles/cdw_hero/public/articles/%5Bcdw_tech_site%3Afield_site_shortname%5D/201907/FedTech-DeepLearning.jpg?itok=nQa1FQBg)

## Synopsis
Here I will be using deep learning recurrent neural networks to model bitcoin closing prices. I will generate two models, one will use FNG indicators to predict the closing price while the other will use a window of closing prices to predict the nth closing price.

Neural Networks themselves are algorithms designed to replicate the human brain and when I say replicate the human brain, I mean the idea of being able to recognize patterns and sensory data. One should then understand why Neural Networks are used in stock predictions. The premise of using RNN's which are specifically Recurrent Neural Networks is then to recognize these patterns and predict what is going to happen next. This sounds even better for making predictions right? One can then put some icing on the cake by using an LSTM RNN which is a Long Short-Term Memory Recurrent Neural Network. A mouthful to say the least. The idea behind the LSTM is the fact that as RNN's are exposed to more data, they are exposed sequentialy, the oldest data is farther and farther back. This eventually leads to loss of information. One could say RNN's have horrible memory. LSTM to an extent put "weights" on the "memories" and virtually keep data that is most influential on the results. 

Here I will be playing with LSTM RNN models, well one specific model used two different ways. The goal is to test out the power of these models and in the process to see if using the Bitcoin Fear and Greed Index or if using windows of Bitcoin closing prices is better for predicting the nth closing price of Bitcoin. My hypothesis is that the windows will be the best bet. 

## Findings
When looking at these models one wants the least loss and you want to see the best predictions without overfitting. I broke my results into three questions:
  
  1. Which model has a lower loss?
      - 
  
  2. Which model track the actual values better over time?
      -  
  
  3. Which window size works best for the model?
      -


