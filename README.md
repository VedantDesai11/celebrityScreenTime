# celebrityScreenTime

Calculate the time a celebrity is on screen for a video by recognizing his face in each frame.

Store single images of the celebrity you want to recognise in the train folder. Folder name should be the celebrity name and in that folder, each image should just be a solo image of the celebrity.

Training data format:
* Data/
  *   Train/
      *   Celebrity1/
          * Celebrity1image1.jpg
          * Celebrity1image2.jpg
          * Celebrity1image3.jpg
      *   Celebrity2.
          * Celebrity2image1.jpg
          * Celebrity2image2.jpg
          * Celebrity2image3.jpg
      *   Celebrity3.
          * Celebrity2image1.jpg
          * Celebrity2image2.jpg
          * Celebrity2image3.jpg
        
Select the video in which you want to find out how much screen time your celebrity gets and run the code.

## Example 

Finding how much time Stevel Carrell gets on screen in an episode of The Office. (Season 03 Episode 02)

Training SVM on images of Steve Carrell and other celebrities taken from the internet. Images located in data/train/

![alt text] (https://github.com/VedantDesai11/celebrityScreenTime/data/train/Steve_Carrell/Steve_Carell.jpg)

Import any episode of the office based on your choice and run the program. 

Output tells you how many minutes Steve Carrell spends on screen.

Frames that detected steve carrell
![alt text](https://github.com/VedantDesai11/celebrityScreenTime/Example/Unknown.png)

![alt text](https://github.com/VedantDesai11/celebrityScreenTime/Example/Unknown-2.png)

![alt text](https://github.com/VedantDesai11/celebrityScreenTime/Example/Unknown-3.png)

![alt text](https://github.com/VedantDesai11/celebrityScreenTime/Example/Unknown-4.png)





