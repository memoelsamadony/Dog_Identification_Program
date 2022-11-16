# Dog Identification program
This is a program is made as a project part of Udacity Data Scientist Nanodegree program ,And its developed to classify dogs to its breed , Also if it has a picture of a human as its input it will find the most resembling breed to him as a funny user experience.

## Table of contents
- [About](#about)
- [Project Details](#project-details)
- [Libraries](#libraries)
- [Examples Using The Program](#examples-using-the-program)
- [credits](#credits)


## About 
This program takes a picture from the user and then classify if its a dog or a human or neither,If its a dog it finds its breed and if its a human it find the most resembling dog breed to him and if its neither it terminates with 'invalid input' statement

Main project Files :

1. dog_app.ipynb : The notebook that contains the code for the program

2. The saved models folder : Contains the files that contain the best weights of the models tried in the notebook

3. The haarcascade folder : contains the main file used in creating the human face detector
               
4. The bottleneck features : contains the files that contain the main weights learned by other models used in the notebook

## Project Details
The project is divided in three main sections (you will find more in the notebook) :

1. First part of building the human face detector and dog detector

2. Second part of building three different models :

        - one from scratch that had above 3 percent accuracy
        - one using VGG16 that had above 40 percent accuracy
        - The last one and the main one used , Was built using transfer learning with ResNet50 that had above 80 percent accuracy

3. Final part of building the algorithm that utilizes the above sections into use , As it takes a picture(its path) from the user as input ,Prints whether its a dog or human, Prints the photo and Prints the dog breed of the dog if its a dog picture or if its a human picture it prints the most resembling dog breed to him.

4. This project includes writing a blog post 


## Libraries 
- keras
- sklearn
- tqdm
- cv2
- numpy
- matplotlib

To install those packges you can use pip or conda install

example : `pip install flask keras` or `py -m pip install numpy`


## Examples Using The Program
Predicting dog breed :

![image](https://user-images.githubusercontent.com/91777656/202276733-a9e77d04-a743-4af4-9329-9b2248c9915c.png)



Predicting the most resembling dog breed for a human picture :

![image](https://user-images.githubusercontent.com/91777656/202278112-43696e27-ae11-4bb8-810b-790410d6168d.png)




Predicting that is neither a dog nor a human picture :

![image](https://user-images.githubusercontent.com/91777656/202277655-c491117c-0c8b-4e59-aae6-b5b9dbafbcb4.png)



## credits 
Many thanks to [Udacity](https://www.udacity.com/) for providing the templates for the code 
