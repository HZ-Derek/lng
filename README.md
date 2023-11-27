# LNG
LNG Price Pridiction
In this notebook we will try to predict the Netflix stock prices using some very well known Machine Learning techniques.

It is important though to be very precise about what we want to predict.

In other words, we are going to split our goals in three parts:

Long Term Prediction
Middle Term Prediction
Short Term Prediction
I want to make this introduction as short as possible so I will explain what I mean while we’re doing it.

# Long Term Prediction

直接用日数据进行建模，然后预测未来三年的日数据，通过观察未来三年的日数据得到未来三年的变化趋势，是可以的，但存在以下几个问题：

**预测结果的准确性可能会降低。**日数据包含了大量短期波动，这些短期波动可能会影响模型的预测结果。如果直接用日数据进行建模，模型可能会过度拟合短期波动，导致预测结果不准确。
**预测结果的解释性可能会降低。**日数据包含了大量细节，这些细节可能会影响模型的预测结果。如果直接用日数据进行建模，模型可能会难以解释预测结果。
**预测结果的应用性可能会降低。**日数据的变化趋势可能具有季节性或周期性，这些趋势可能会影响模型的预测结果。如果直接用日数据进行建模，模型可能会难以捕捉这些趋势，导致预测结果的应用性降低。
