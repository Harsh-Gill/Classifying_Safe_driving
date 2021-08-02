# ML_Driving
This is for self-writing code to solve the distracted driver problem.


This competition is from the Kaggle competition of distracted drivers at : https://www.kaggle.com/c/state-farm-distracted-driver-detection/

The aim of this competiton as stated in the website :

According to the CDC motor vehicle safety division, one in five car accidents is caused by a distracted driver. 
Sadly, this translates to 425,000 people injured and 3,000 people killed by distracted driving every year.

State Farm hopes to improve these alarming statistics, and better insure their customers, 
by testing whether dashboard cameras can automatically detect drivers engaging in distracted behaviors.
Given a dataset of 2D dashboard camera images, State Farm is challenging Kagglers to classify each driver's behavior.
Are they driving attentively, wearing their seatbelt, or taking a selfie with their friends in the backseat?





It is a simple model using transfer learning from the VGG-16 architecture, it resizes the driver images to fit the transfer learning. It uses Keras code to define data generators and uses categorical accuracy metric to determine model accuracy.

![Alt text](https://neurohive.io/wp-content/uploads/2018/11/vgg16-neural-network.jpg "Title")
# credits to : https://neurohive.io/en/popular-networks/vgg16/



The model currently places in the top 20% in the Kaggle leaderboard, with a score loss of 1.58852
Its accuracy on the test and train model is around 80% currently.


