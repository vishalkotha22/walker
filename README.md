# Walker
An app that detects real time camera footage and finds objects via YOLO v3 and converts the object to text to speech for the blind to hear.
This code is not meant to be run without a specific virtual environment with all the packages installed. Winner of HackTJ's best Artificial Intelligence/Machine Learning hack.

[Devpost link](https://devpost.com/software/walker-5ftn0l)

## Inspiration

We first thought about this project after seeing an object detection lesson at TJ’s Machine Learning Club. We also noticed that there is a lack of accessibility for disabled people. We decided to expand on this concept by incorporating real-time analysis and implementing text to speech. Our vision is to have people experience vision. We hope Walker can make everyone walk.

## What it does

Walker is a program that takes in an image of the surroundings and relays information about it in an audio format. This can be used to help people with weak eyesight or blind people to understand their surroundings.

## How we built it

We first used OpenCV and YOLO for object detection to find objects within the camera frame, we then used image analysis to find the depth and location of the object. Based on this information, we created a sentence that was inputted into Google Text to Speech to create an audio file that will be played.

## Challenges we ran into

It was hard to collaborate this year especially in an online environment. We tried out software such as Google Colab, but it resulted in technical issues. We solved this by creating a system where one person works on the final code in a virtual environment, and the rest work on `methods and chunks of code to add to the final code. This allowed us to create an efficient system to create the app.

## What we learned and what we are proud about

Although we know a bit about Machine Learning, we didn't know much about Computer Vision. We learned about packages such as OpenCV and YOLO and used them to create the application. We are proud of our program because we found a cool idea, and although we didn't know some fo the packages, we learned about it and applied it to the software.

## What's next for Walker

We hope to make Walker a fully functional mobile app to allow it to be more accessible to the general public. We also believe that we should implement a cloud computing software such as AWS or Azure to allow the program to be more efficient and not run locally. Another idea we have that we can make it so it can see people or objects behind or above using a 360 camera, and mapping it so the audio of a specific object comes from that direction using spacial audio.

## Video

https://www.youtube.com/watch?v=qTKBg_7uRKs

Contributors: Rithvik Reddygari, Vishal Kotha, Hamzah Jamal, and Arnav Jain
