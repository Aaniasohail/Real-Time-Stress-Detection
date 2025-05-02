# Real-Time-Stress-Detection
Real-Time Stress Detection through Facial Expressions Analysis

In today’s era, stress has become an inevitable part of our lives. It is affecting individuals across many domains such as education, personal relationships, and work. The stress that is caused due to various factors is invisible in nature but can be predicted by the humans’ behaviors and actions. The most natural form of non-verbal communication is facial expressions, it gives an understanding of emotional states and stress is also considered an emotional state. Stress is a mixture of mental and physical reactions that take place when someone undergoes a difficult situation. 

When a person is in stress, it makes the person feel tensed or emotionally tired. The eyes might look wider in this state, the pupils get bigger and it feels like if the person is staring. In some situations, the eyebrows may rise, and some lines can be observed on the forehead, which shows that the person is emotionally upset. Similarly, lip compression and jaw tension are also signs of stress. Like these symptoms, there are also some micro-symptoms that can be used to understand the small emotional reactions such as, slights change in the skin color and quick movements of facial features. Considering and adding all of these details in a stress detection system, will lead to a more accurate detection. This will make it better at spotting complex signs of stress on a person’s face. 

In this study, we focus on real-time stress detection through facial expressions using transformers. This research is conducted in an educational institute of Pakistan. The Vision Transformer model is our primary deep-learning architecture for the stress detection. To implement this architecture, Facial Expressions Recognition Dataset (FER 2013) and Stress Faces Dataset (SFD) are being used. 

Facial Expressions Recognition dataset (FER 2013) covers the seven facial expression classes. These facial expressions are efficiently detected by using the Vision Transformer-based model with the Haar-Cascade classifier. The output obtained classifies the facial expression, then this expression is further sub-categorized as ‘stress’ or ‘no stress’. The interface shows the labeling of face on the interface and the bars indicating the continuous change in the values of facial expressions in a real-time scenario. Stress Faces Dataset (SFD) consists of two classes stress and no stress. The dataset has two sections further in each class, train and test. The Vision Transformer-based model with the Haar-Cascade classifier is used to accurately detect the ‘stress’ and ‘no stress’ on the person’s face. The output is presented on the interface with the box outlining the face area and values of ‘stress’ and ‘no stress’ mentioned in percentage value. 


The project has the following key objectives:
•	To develop a real-time facial stress detection system, which will accurately detect and classifies individuals as ‘stress’ and ‘no stress’ using a Vision Transformer model.
•	To implement a webcam-based interface that will continuously capture input images and the detecting the faces from those images to visualize the stress levels on screen.



Dataset URL:

Stress Faces dataset:
https://www.kaggle.com/datasets/janithukwattage/stress-faces-dataset

FER dataset:
https://www.kaggle.com/datasets/deadskull7/fer2013
