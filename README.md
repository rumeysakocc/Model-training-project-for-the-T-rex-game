Self-Playing T-Rex Game with Deep Learning  
--------------------------------------------------------------------------------------------------
## ✓ Project Description: 


This project features a self-playing T-Rex game agent powered by a deep learning model. 
The T-Rex game, also known as the "No Internet Dinosaur Game," is a simple yet addictive web-based game where the player controls a running T-Rex that must jump over obstacles.
 
During the data collection phase of the project (trex_getdata), I played the game myself for a while, I wrote a code that takes a screen image when I press each key.
Since the overall screen is not of interest to us, I set the frame that would be most accurate for me in the "Paint" programme.

![Trex_GetData](https://github.com/KocHanim/Model-training-project-for-the-T-rex-game/assets/115664157/7f53092d-a0ab-45bb-ab56-e832494a49eb)

To make it easier to label the screenshots I took, I assigned the name of each saved image to the key I pressed, so I was able to label them with a single python code during the tutorial (label = filename.split("_")[0]). I am leaving a picture for example!

![296Data](https://github.com/KocHanim/Model-training-project-for-the-T-rex-game/assets/115664157/fa623cf8-6a9e-4245-b400-4da36b9809e9)


I have to make the first jump for the model to work. 
If we do more data and labelling during training, we can get better results. I used 300 screenshots for this model.

https://github.com/KocHanim/Model-training-project-for-the-T-rex-game/assets/115664157/01f8a96d-34e9-4db8-b31e-29db1de33731

--------------------------------------------------------------------------------------------------
## ✓ Key Features: 


Deep Learning Model: The core of the project is a convolutional neural network (CNN) trained to play the T-Rex game automatically by analyzing the game screen. 


Data Collection: The model has been trained on a dataset of game screen captures obtained using screen recording techniques.


Game Environment: The code provides access to the T-Rex game, which can be found at https://fivesjs.skipser.com/trex-game/.
 
Data Preprocessing: The collected images are processed and transformed into suitable input data for the deep learning model.


Training: The deep learning model is trained using the preprocessed data to predict actions (jump, duck, or do nothing) based on the current game screen.  


GitHub Repository: This project's code and model weights can be found in this GitHub repository.


--------------------------------------------------------------------------------------------------


## ✓ Usage: 

You can use the trained model to play the T-Rex game automatically or experiment with the model for further improvements.


--------------------------------------------------------------------------------------------------


## ✓ Requirements: 

Python 3.x Dependencies as listed in the code


--------------------------------------------------------------------------------------------------


## ✓ Contributions: 

Contributions and enhancements to the project are welcome. Feel free to fork and submit pull requests :)


--------------------------------------------------------------------------------------------------
## ✓ Author: 
 
Rumeysa KOÇ
