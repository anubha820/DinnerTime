<snippet>
  <content>
# DinnerTime
This is the project for Columbia University COMSE6998 Fall 2016, by Marshall Van Loon, Anubha Bhargava, Patrick Cao, Zoltan Onodi-Szucs.

We propose an application hosted on cloud services that infers the ambiance and styles of restaurants based off of user-uploaded images.  Our algorithm will process images on Amazon EC2 instances pre-trained with a convolutional neural network and return the style. The result will provide users with additional information that will aid them in selecting the right restaurant.

Division of Work:
Anubha Bhargava - mobile application
Marshall Van Loon -  dataset generation through web-scraping
Zoltan Onodi Szucs - neural network and algorithm design
Patrick Cao - website and database development

The system can be divided into three major parts:
1. Front end with the mobile application and the website
2. Auto-scaling group for prediction and machine for model training
3. Auto-scaling group for preprocessing and web scraping data

Architecture Flowchart:
![alt tag](https://github.com/Patricknew/DinnerTime/blob/master/Architecture.png)
