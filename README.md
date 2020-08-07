# Emotion-Detection-From-Face-Images

The main goal is to make a model that can predict a person's emotion and key facial points from images of their faces.

Artifical Emotional Intelligence is a branch of AI that enables computers to understand human verbal and non-verbal cues, including facial expressions, which is what we shall focus on.

The goal of this project is being able to classify peoples emotions based on their face pictures. We will develope, evaluate and deploy 2 Residual Convolutional Neural Networks, one to classify peoples key facial points and another one to classify their emotion. We will use the predictions from both of this models to obtain more comprehensive information of the person's emotion.

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. There are 22,000 face images total, 20,000 of which will be used to train the Emotion Recognition model , and 2,000 for the Key Facial Points model.

the Key Facial Points model can be a building block in several applications, such as:

- tracking faces in images and video
- analysing facial expressions
- detecting dysmorphic facial signs for medical diagnosis
- biometrics / face recognition.

### Key Facial Points:

- (x,y) coordinates of the center of the eyes
- (x,y) coordinates of the inner and outer corners of the eyes
- (x,y) coordinates of the inner and outer ends of the eyebrows
- (x,y) coordinates of the left and right corners of the mouth
- (x,y) coordinates of the center of the upper and bottom lip

### Emotions:

- 0 = Angry
- 1 = Disgust
- 2 = Sad
- 3 = Happy
- 4 = Surprise
 
## Libraries used:

### Data preprocessing and visualization:

- sklearn, pandas, numpy, matplotlib and seaborn 
  
### Model developement, evaluation and deployment:

- Tensorflow with Keras API for developement.
- sklearn for evaluation evaluation
- Tensorflow serving for deployment

### Acknowledgements:

- https://www.udemy.com/course/modern-artificial-intelligence-applications

- Datasource: https://www.kaggle.com/c/facial-keypoints-detection/overview

 - This dataset was graciously provided by Dr. Yoshua Bengio of the University of Montreal

- Datasource: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

 - This dataset was prepared by Pierre-Luc Carrier and Aaron Courville, as part of an ongoing research project.
