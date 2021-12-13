# Strawberry cluster complexity analysis and harvest time estimation, multi class segmentation using U-Net
 Tools: Python, Linux, Tensorflow, Keras, CUDA, Computer Vision, Deep Learning, Jira, GitLab

# Objectives: 
The main objective of this project is to develop a complexity detection system to improve the  perception, estimate the time of harvesting and to locate the plucking points of the strawberries while the robot is harvesting. The following are the requirements of the system:

• Detect and localize the strawberries depending upon the complexity to pluck.

• Localize the plucking point.

• Estimate the time of harvest.

• Localize the strawberries in 2D and 3D.

• Ability to work in any strawberry farm conditions

# Achievements 

The following are the achievements obtained by doing this project:

• The AI model developed was able to detect the strawberries based on the complexity including the heavily occluded ones in the cluttered environment.

• The system improves the perception by providing the detections so that the robot should further manipulate in the environment to improve the detections.

• The U-Net model makes use of semantic segmentation to segment each class of strawberries and albumentations to multiply the training images taken under various light  conditions to improve the predictions.

• The model can be used on any kind of strawberry farm conditions and is capable to localize the strawberry picking points in 2D. 

• The estimated time of harvest is also calculated according to the fruit occlusions and cluttered environment. This data is calculated mathematically using rough estimates of 
plucking fruits of different complexity levels. 

## Dataset: 

Prepared using images taken using smartphone from the strawberry farm
Images are labelled to 4 classes depending upon the complexity to pluck the berries
Masks are prepared using polygon labelling in apeer.com
![image](https://user-images.githubusercontent.com/51755694/145883457-bebb02de-db64-4440-99a0-f31c30da9d66.png)


## Novelty
Complexity analysis of plucking fruits is a novel topic and the machine learning model is trained using ripe strawberries classified as easy, medium, hard and very hard depending upon the complexity to harvest. The U-Net model has a robust architecture and is widely used in the medical field for detection of tumours, cancer cells etc. In this project U-Net is implemented for multiclass semantic segmentation. Active perception is achieved using 2D cameras to classify the strawberries and to find the picking point and to estimate the time of harvest. Calculating all these from a single detection is hard but the model was able to give enough information to improve the detection. This  project also helps the robot to completely detect all ripe the strawberries and gives the input to the system to further manipulate and explore the environment in case of detection of heavily occluded berries. The total detection of fruits to be harvested is still a novelty and the system is now able to detect and explore the environment
  
Prediction:
![image](https://user-images.githubusercontent.com/51755694/145883391-216a67f7-976c-4e5a-9874-89e4eea34439.png)
