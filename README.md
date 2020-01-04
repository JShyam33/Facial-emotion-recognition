# Facial-emotion-recognition
Facial emotion detection using custom made keras sequential  model.

1) we import libraries that we will use in the code.

2) we set important variables and model path this are set according to colaboratory directory.

3) I made the train generator to generate training instansces.

4) Made keras sequential model. I tried 2-3 architecture for the network and found that this works decent. 
More improvement can be made. with this architecture model is successfully detecting emotions like anger, happy, sad etc.
some emotions like disgust are hard to detect due to limited no of examples.

5) To train the network i used kaggle emotion recognition dataset with images belonging to 7 different emotions.

6) lastly i used opencv haarcascade to locate the face crop it then feed it to network for detection. 
i have coded for detecting emotion in single image as well as for video.

7) by changing videofeed to 0 we can do real time facial emotion detection.
