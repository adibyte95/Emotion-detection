# Emotion detection
To detect seven human emotions<br/>
1.Angry <br/>
2.Disgust <br/>
3.Fear <br/>
4.Happy <br/>
5.Sad <br/>
6.Surprise <br/>
7.Neutral <br/>

<br/>

## Dataset
Kaggle dataset was used <a href = "https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data">here</a>
<br/>

## Accuracy
Training accuracy : 66 percent <br/>
Testing accuracy : 62 percent <br/>
<br/>


## Confusion matrix
confusion matrix for the test set containing nearly 7k examples<br/>
<img src = "https://github.com/adibyte95/emotion_detection/blob/master/confusion_matrix.png" alt ="confusion matrix">
<br/>

## learning curve
learning curve <br/>
<img src="https://github.com/adibyte95/emotion_detection/blob/master/loss_curve.png" alt = "learning curve" />
<br/>

## Note
After 50 epochs the model was starting to overfit with very minute increase in test accuracy so i used early stopping . Dropout is used to reduce the overfitting for the model. However an accuracy of ~63-64 percent can be achieved if the model is trained further<br/>
I am open to pull requests and suggestions for improvement of results
<br/>
