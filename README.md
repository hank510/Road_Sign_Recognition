# Road_Sign_Recognition
Project to detect and recognise road signs at low visibility conditions and convert the output to speech to help the driver drive accordingly. 
The dataset contains 17000 images in total with 8000 high quality images(1080p x 1080p), 5000 lower quality(720p x 720p) and 3000+ very low quality images(<30p). 
The dataset has been divided into 3 portions for training and testing with 75% to be used for training and validation and testing with 25% of the images.
Link to the dataset: https://www.kaggle.com/datasets/vrushankanand/road-sign-detection

The training of the dataset was done on YOLOv7 architecture with, 185 classes and trained the model for a total of 300 epochs. The final accuracy gained after testing was acheived to be 96.7%.
Link to the notebook: https://www.kaggle.com/code/vrushankanand/road-sign-detection-yolov7
