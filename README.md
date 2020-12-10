# Digit recognition webapp test
## Model:
We trained a deep learning model on the MNIST dataset for 10 epochs and 32 batches with 20% validation split.
## Accuracy:
The testing accuracy of this model is 99%.

[INFO] evaluating network...
              
              precision    recall  f1-score   support
        zero       0.99      0.99      0.99      1148
         one       1.00      0.99      0.99      1380
         two       0.99      0.99      0.99      1184
       three       1.00      0.99      0.99      1252
        four       0.98      1.00      0.99      1191
        five       0.99      0.99      0.99      1093
         six       0.99      0.99      0.99      1148
       seven       0.99      0.99      0.99      1219
       eight       0.99      0.99      0.99      1166
        nine       0.99      0.98      0.98      1219
        
    accuracy                           0.99     12000
    macro avg       0.99      0.99     0.99     12000
    weighted avg    0.99      0.99     0.99     12000

## Model deployment:
1. Firstly, we converted the model to Tensorflow.js and saved it.
2. We used the HTML file 'tfjs.html' from https://github.com/carlos-aguayo/carlos-aguayo.github.io to create a webpage for the model, with slight changes in the body and style.


### Try it here: [Digit recognition WebApp](https://msamir9.github.io/Digit_recognition_app/ "Digit recognition webapp")

