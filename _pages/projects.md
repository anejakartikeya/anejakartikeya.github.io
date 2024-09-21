---
layout: page
title: Projects
permalink: /projects
bigimg:
  - "/img/big-img/Projects.jpeg"
---


## Developed a Handwritten Digits Classifier with PyTorch, 08/2024
* Preprocessed the MNIST dataset for handwritten digit recognition, build a neural network, train and test the neural network

## Capstone Project, Full Stack Developer Nanodegree, 08/2024
* Constructed a database-backed web API with user access control. 
* Built API endpoints for the application and secured them for use in front end web application. 

## Deployed a Flask App to Kubernetes Using EKS, 07/2024
* Created a container for Flask web app using Docker and deployed the container to a Kubernetes cluster using Amazon EKS. 
* Use automated testing to prevent bad code from being deployed and monitor their app’s performance using AWS tools. 

## Identity Access Management, 07/2024
* Built the backend for a coffee shop application. 
*	Added user accounts and authentication and used role-based access management strategies to control different types of user behavior in the app. 

## Trivia API, 07/2024
* The app can search for trivia questions and answers via category and difficulty. 
* Added new questions. 
* Modify the difficulty rating of questions. 


## Design a Venue Booking Database, 07/2024
* Developed artist/venue booking application for a fictitious startup Fy-yur. 
* Used SQLAlchemy and PostgreSQL, enabling artist and venue management, including sign-ups, availability listings, and browsing options for bookings.

## Resiliency Enhancement, 05/2024
* Collaborated with a PhD student to support his project for Sandia Laboratories,
* Focused on Machine Learning analysis of a dataset measuring the accuracy of a processing unit under various types of attacks

## Some Projects at UW Madison during BS, 2023
* Projects implementing Data Cleaning, Standardizing Data, K-Means, PCA Analysis, K-Nearest Neighbor, Decision Tree, Linear and Multiple variable Regression, Polynomial Regression (Python)
* Implemented RedBlack Tree data structure (Java)
* Developed a simple music app utilizing RedBlack Trees for data storage (Java)
* Implemented Dijkstra's Algorithm (Java)
* Developed a hash table data structure (Java)
* Hospital priority queue system functionality (Java)
* GUI project featuring an animated walking man (Java)
* Simple GUI project game (Java)
* Twitter feed functionality: create tweets, like, retweet, maintain chronological order using linked list (Java)
* Password cracking: implementation with min/max heap of common passwords prioritized for cracking (Java)
* Implemented Full Adder, Ripple Carry Adder, Encoders, Decoders, Comparator, Waveform Detectors, BCD Adders, BCD Subtractor (Verilog)



# Steganography

​	[Github with Jupyter Notebook](https://github.com/anejakartikeya/steganography)

* This is my school project (AS Level) under Mr Simon Carter. In this project, I embed the text message inside an image so that the text message is hidden
  * I created an odd-even algorithm using Python. I flattened the image pixel value array using numpy and reserved first few bits to store the length of the message. The length of the message is a key to encrypt and decrypt. Data bits are encoded after the reserved bits.
  * For encryption, I converetd the text message to ASCII code and then matched the pattern in the image pixels values e.g. if the text code is 01100001 then I checked pixel value of image of eight pixels and ensured that it has even value if the text corresponding code is 0 and odd if 1, in case it is not then I changed it to match. Thus, pixels values after encryption shold be even, odd, odd, even, even, even, even, odd. Changing pixel value by one has no visual impact on the image.
  * For decryption, I first checked the reserved pixels to get the length of the message and then checked the pixel values for odd/even from the starting position of data pixels and until message length.



# Early Robotics

## Gripper Robot

* I developed a gripper robot in 2016 using Lego Mindstorms that rotates until it senses an object then picks it up and delivers it
* [Demo at Youtube](https://www.youtube.com/watch?v=Ng2njUWPeyc)

  <iframe width="420" height="315" src="https://www.youtube.com/embed/cGsvFYrOfUI" frameborder="0" allowfullscreen></iframe>

  

## Spiker Robot

* I developed a spiker robot in 2016 using Lego Mindstorms that walks a set distance then loads and shoots a ball
* [Demo at Youtube](https://www.youtube.com/watch?v=8SYe0h6aAM4)

  <iframe width="420" height="315" src="https://www.youtube.com/embed/8SYe0h6aAM4" frameborder="0" allowfullscreen></iframe>



# Android App

LogoQuiz: [https://apk.support/app/appinventor.ai_KartikeyaAneja.LogoQuiz_KartikeyaV2](https://apk.support/app/appinventor.ai_KartikeyaAneja.LogoQuiz_KartikeyaV2)

I developed a LogoQuiz Game in 2014 using [MIT App Inventor](https://appinventor.mit.edu)

* The app shows logos as questions and offers four multiple choice options for the player



