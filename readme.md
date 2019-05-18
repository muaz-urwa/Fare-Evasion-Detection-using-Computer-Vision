## Turnstile Jump Detection:  
- A proof of concept classifier which classifies each image as person <b>jumping</b> or <b>walking.</b>
- About 100 images of people walking 100 images of people jumping are used to train classifier.
- [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) is used to extract 18 key point on human body for each image.
- Random Forest Classifier is trained on these key points after some feature engineering. (default hyperparameters)

- Classifier gives about 90% accuracy even with a train/test split of 50/50 indicating that it is an easy classification problem.

[Notebook](https://github.com/muaz-urwa/Projects/blob/master/ComputerVision/PoseEstimation/urwa_TurnstileJumper_demoTest.ipynb)

## Normal Rider
<img src="urwa_walk.gif">

## Turnstile Jumper
<img src="urwa_jump.gif">
