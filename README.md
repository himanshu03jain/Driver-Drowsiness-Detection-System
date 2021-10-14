# Driver Drowsiness Detection 

It is my college project with 2 team members more using machine learning.

It can prevent accidents that are caused by drivers who fell asleep while driving and calculate scores, if this score limit is high then the alarm will ring.
## Scope
The scope of the Drowsy Driver Detection in the modern period is to diminish the vehicle street mishap and furthermore this project is utilized for security reasons for a driver as it reduces car accidents. The fatigue detection system in this project is capable of detecting drowsiness on drivers and then based on the current situation will alert the driver using an alarm.

## Problem statement
Fatigue is a safety problem that has not yet been deeply tackled by any country in the world mainly because of its nature. Fatigue, in general, is very difficult to measure or observe unlike alcohol and drugs, which have clear key indicators and tests that are available easily. Probably, the best solutions to this problem are awareness about fatigue-related accidents and promoting drivers to admit fatigue when needed. The former is hard and much more expensive to achieve, and the latter is not possible without the former as driving for long
hours is very lucrative.

## Technology used 
> Pyhton

> Machine learning

> Image processing

* Some pyhton libraries used in this project are- numpy, keras, tensorflow, OpenCV, Pygame 

## Algorithm
Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy.

## Dataset
The dataset used for this model is created by us. To create the dataset, we wrote a script that captures eyes from a camera and stores in our local disk. We separated them into their respective labels ‘Open’ or ‘Closed’. The data was manually cleaned by removing the unwanted images which were not necessary for building the model.
Or, you can download the dataset from kaggle [click here](https://www.kaggle.com/serenaraju/yawn-eye-dataset-new)

## Screenshots
Awaken and sleeping person

![alt text](https://github.com/himanshu03jain/Driver-Drowsiness-Detection-System/blob/master/Presentation/FaceCapture.JPG)

## Flow chart
![alt text](https://github.com/himanshu03jain/Driver-Drowsiness-Detection-System/blob/master/Presentation/flowchart.JPG)
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
