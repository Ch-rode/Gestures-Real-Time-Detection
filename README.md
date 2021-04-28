# Gestures-Real-Time-Detection


This was an attempt at **TensorFlow object detection** to distinguish between 4 **different gestures** (rock, open, thumb up, thum down), using **LabelImg** to label the location of the objects in each single image. Most of the time used in the creation of the project was dedicated to the creation of the corpus of images, in particular to gather diverse sets of images, for example, images with different shades of backgrounds and objects at different angles. In any case it would be better to use more images to increase the accuracy and consistency of the model.   

For this project, the module used for training and Testing is [here](https://github.com/tensorflow/models/research/object_detection)

Furthermore, it has been included the possibility of detaining in real time what shape our hand is taking through the PC video camera, by opening a video window.
