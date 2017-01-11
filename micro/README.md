OpenCV using KNN to match text

I will recomend Chris Dahms Videos, he does a good job of explaining what's happening and why.

https://github.com/MicrocontrollersAndMore/OpenCV_3_KNN_Character_Recognition_Python

The training code is incomplete, since the code that Chris originally wrote is interactive with the
terminal. Jyupter notebooks don't support that interaction model, but this is a good implementation.

One of the big changes is that TestTraining is now very pythonic, as opposed to being a VisualBasic version of Python

Files --

* TestTraining -- Given the training set and the example image display
* GenData -- A draft implentation of the program to train the input set (not really working), since it's interactive
* Train -- Given the output of GenData train the recoginzer
