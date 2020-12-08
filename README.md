# APS360-project
This project focuses on identifying clothing items in a given image and categorizing them. There are a variety of potential applications for this in the fashion industry in identifying desired clothing items and producing recommendations, as well as in forensic investigations to help identify individuals based on their clothing. The growing accessibility and popularity of social media means that millions of photos are posted each day which could be used to identify real-time insights into fashion trends. As the fashion market changes rapidly, fashion retailers could leverage access to real-time market data and a machine learning approach to gain an advantage over their competitors in trending items.

In this project, machine learning will be applied to train a model on a large set of images containing a variety of clothing items worn or not worn to predict the category of the items. A machine learning approach will be useful in this case for its ability to identify edges and shapes of items in various configurations. It allows the application to learn from these training images and be able to identify the same patterns in new images. Without machine learning, this task would be very difficult to tackle given that there is so much variability in the angling, positioning, colouring and design of the clothing items in different photos.

Final Notebooks Folder has the final files for this project.

Data_Processing: You can find the code used for data processing and augmentation in Data_Processing.ipynb

Best Model: The code for the model with the highest accuracy can be found in Final_Alex_ANN_84__30min.ipynb [AlexNet+ ANN]

Preliminary Model with no features (16000 images): Final_16k_CNN_tuned_project.ipynb (CNN model with 2 convolutional layers, 2 max pool layers and 2 fully connected layers)

VGG+ANN Model: Final_16K_ANN_VGG_features.ipynb

Baseleline models:

VGG+SVM:Final_16K_VGG_SVM.ipynb

VGG+RandomForest:Final_16k_VGG__RandomForest.ipynb

AlexNet+SVM:Final_16k_SVM.ipynb

AlexNet+RandomForest:Final_16k_AlexNet__RandomForest.ipynb

Code Used for testing the holdout dataset: holdout.ipynb

Code Used for project demo: Project_Demo.ipynb
