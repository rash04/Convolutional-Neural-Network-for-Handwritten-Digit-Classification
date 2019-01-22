# Convolutional-Neural-Network-for-Handwritten-Digit-Classification #
This is the code for a Convolutional Neural Network used to classify the largest Handwritten Digit written above an image. This entry received 93% accuracy at the Kaggle competition it was coded for.

A VGG inspired architecture is used to classify the handwritten images, after 95-5 split of the training data was made. Please note that the code used to preprocess the data is a part of ConvNet.ipynb and essentialy attempts to find the largest digit (by bounding box - manually coded) and separate the digit from the backgound by using its darker pixel values as a threshold.

If you have any questions regarding the CNN implementation/results, feel free to contact me (rashik.habib@mail.mcgill.ca)

	Each cell has a labelled cell # above it. Please follow the steps below based on those cell #s:
		1. Run cell #0 - for necessary imports
		2. Run cell #2a and then cell #2b - to preprocess the datasets
		3. Run cell #4 - to train the CNN
		4. Run cell #7 - to generate the prediction file and save it
	
	If there is some error in the steps above, please use the following steps to obtain the files using Google Drive:
		1. Run cell #0 - for necessary imports
		2. Run cell #1 - to set up PyDrive. Please ask me (Rashik Habib) for the authentication password to my google drive.
		3. Run cell #2c - load the pre-processed data from the google drive
		4. Run cell #4 - to train the CNN
		5. Run cell #6 - load the pre-processed test_x from google drive
		6. Run cell #7 - to generate the prediction file and save it
