collect_imgs.py file which is used to collect the images/gestures from the live video stream using the openCV and it captures upto 100 frames and we can specify based on our requirements.
create_dataset.py file which is used to recognize only the hand and its size, shape and its movements and using the mediapipe framework, recognises the coordinates of the hand and it also gives the x,y,z coordinates for the hand which is easier to figure out the hand gesture. finally it creates a dataset for the recognized images.
train_classifier.py file which trains the dataset which is created on above using the algorithm called randomforest algorithm. and it generates a pickle file.
inference_classifier.py by running this file, and showing the gesture it shows the result in the form of text along with it also shows the hand pipe of the hand gesture which is got using the mediapipe. and the result will be displayed at the top of the gesture in the text form only.

NOTE: Make sure that the execution of files in the above order only. 
