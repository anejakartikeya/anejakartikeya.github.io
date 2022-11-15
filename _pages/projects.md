---
layout: page
title: Projects
permalink: /projects
bannerIMG:
  - "/img/bannerIMG/Projects.jpeg"
---

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



