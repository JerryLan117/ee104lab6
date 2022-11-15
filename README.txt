EE104 lab7 use CNN (Convolutional Neural Network) to recognize color images and use different methods to improve the accuracy.
Jerry(Jiun Jye) Lan partner Anh Nguyen
------------------------------------------------------------------------------------------------------------------------------------------------
1.	Install necessary Python packages
	pip install tensorflow	
	pip install keras
	pip install h5py
	pip install Matplotlib
	pip install numpy

2.	CIFAR-10 Data Set: https://www.cs.toronto.edu/~kriz/cifar.html
	10 different classes: airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.
	
	Develop a CNN From Scratch:
	https://machinelearningmastery.com/how-to-develop-a-cnn-from-scratch-for-cifar-10-photo-classification/

3.	perform the steps outlined
	https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/images/cnn.ipynb#scrollTo=WRzW5xSDDbNF
	This baseline code achieved a test accuracy of over 70%.
	->follow/open the file: cnn.py
	->you could see the we are increasing the accuracy 70% to 87%
	->line 40 Create the convolutional base, which add more on the model
	->line 62 Add Dense layers on top
	->line 70 Compile and train the model

4.	example from the lecture open CNNbaseline.py to learn AND open the test_impage.py to test the images
	open the text.py that we created to increase the accuracy 70% to 90%+

5.	Game Development: open chapter 8 folder Chapter 8 Balloon Flight and open ballon_flight.py
	change any images you like in the images file
	change line 17, 21, 25, 29 different actors
	change line 34 to 37 true or false when you want to let bird going up or down, game over or not
	change line 45 to record the scores that create the text file
	change line 114, 129, 135 to speed up the actors moving  
	
	Hacks and tweaks 
	More high scores
	Speed it up
	File handling
	Level up