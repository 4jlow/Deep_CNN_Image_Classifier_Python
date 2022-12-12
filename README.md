# Deep_CNN_Image_Classifier_Python
CNN Model for Image Classifier built using tensorflow and keras. Distinguishes between dogs and bread

For the next step up from a basic machine learning model, I wanted to do an image classification. There were old jokes about classifying the difference between
corgi butts and bread, or beagles and bagels that I wanted to do one myself. I also wanted to use it as a segway to become more familiar with python from R.  
<br>
I have found someone who did the same project: https://github.com/Kawaeee and found that I didn't understand any of the functions that were in his Model class. 
After connecting, he did provide his dataset, which was compiled using a google chrome extension, so I had 6000+ images to work with to build the same model myself.  By building the model step-by-step, I could then follow each part in Kawaeee's own model and understand its parts. 

<br> 

Throughout this project, I yielded a model with a test and validation accuracy of 97% and 95% respectively with losses of 0.2, and 0.2. The losses were initially above 0.4
for the validation model, so I had to apply some regularization techniques to reduce the validation. While a loss of 0.2 also isn't that great, I decided to end training,
since it seemed like the model would get the vast majority of cases with some outliers. 

<br>

Below are some tricky cases that I handpicked to test how well I could trick the model. Unlike normal regression or linear regression models, the exact parameters 
that the model builds are difficult to see. But through subjective judgement (which can be completely biased and wrong), it seems a main parameter are the clear edges that appear on 
most bread pictures vs the more ambiguous outlines in dog pictures.

Model Results:

Failures:
<br>
![Fail1](https://github.com/4jlow/Deep_CNN_Image_Classifier_Python/blob/master/result%20pictures/Failure_1.JPG)

Successes:
<br>
![Success1](https://github.com/4jlow/Deep_CNN_Image_Classifier_Python/blob/master/result%20pictures/Success_1.JPG)
<br>
![Success2](https://github.com/4jlow/Deep_CNN_Image_Classifier_Python/blob/master/result%20pictures/Success_2.JPG)
