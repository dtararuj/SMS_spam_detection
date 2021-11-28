# SMS_spam_detection
Classification model to detect whether sms is a SPAM or not


In this case we had to detect spam in text messages.  

The best results we achived using neural network with:
- 1 recurential layer and 8 Units,
- emedding layer with size 40,
- Dense layerwith 2 units and softmax activation layers as an output 
- binary_crossentropy loss function,
- Adam Optimizer with learning rate = 0.01


Our model results is:
- 99% accuracy in general, 
- 99% precision for both classes,
- 96% recall in Spam class.

Our results tell us that final model can detect 99% of spam, classifing correctly certain message as a spam with 96% probability (recall).
