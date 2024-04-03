**KAGGLE CentraleSupélec course DeepLearning**

*Ranking : 1/27*
accuracy : 0.97

The task at hand is to classify 296 videos into two categories, "use_sword" and "sword_drawn", with the metric on the test set being category accuracy.

For this kaggle challenge, it is highly recommended to use a pre-trained network for video classification due to 1/ videos being quite heavy to process (optimising the hyperparameters isn't going to be as easy as it usually is), 2/ the limited amount of training data available. Although it is possible to train from scratch, transfer learning can often lead to better results. An example pre-trained network that could be used is "Kinetics400" which is available on PyTorch.

A tutorial notebook is also available on GitHub (https://github.com/JasonMendoza2008/KaggleSwordVideoClassification) to help with implementation as we never dealt with Video Classification tasks in class (cf. https://www.youtube.com/watch?v=PTQudKynRew to help you understand the subtleties of the notebook). There is no transfer learning in it, but it is good enough to get more than 50% accuracy which is what you would obtain if you only submit random answers. You are expected to perform better than the results obtained with the notebook.
