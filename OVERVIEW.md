# Overview of Program

I used Yolov7 with Detectron2 and Python LabelMe to train an object detection model on a dataset that included both ad labels and street signs. 
Then I trained the model for 998 iterations and were able to achieve good performance on test images, but the model's performance on street signs in 
video was not as good. One potential reason for this could be the limited amount of data you have for street signs. 
In machine learning, it is generally the case that the more data you have, the better your model will perform. 
This is because the model is able to learn more patterns and features from the data, which can improve its generalization ability and accuracy on unseen data.
With only 80 images in your dataset, the model may not have sufficient information to accurately detect and classify street signs in video. 
To improve the model's performance on street signs, I could try collecting more data specifically for street signs and incorporating it into the training 
dataset. This should give the model more examples to learn from and may improve its accuracy on street signs in video.

It's also worth noting that there could be other factors that could impact the model's performance on street signs in video, such as the quality and resolution 
of the video, the lighting conditions, and the presence of other objects that may be occluding the street signs. These factors could also affect the 
model's overall performance and should be taken into consideration when trying to improve the model's accuracy.
