# Neural Network (Phase 2)
In this project, with the ```TensorFlow``` library and using the ```Keras``` high-level interface, I have investigated some issues related to neural networks.

 ## Project Description

 In this project, using neural networks, I have recognized the race of each person based on his/her face image. With the help of the ```Keras``` interface, I have created a FeedForward network that includes at least two hidden layers (taking into account the input and output layers (softmax), the network has 4 layers.)

I have read data using ```Keras``` interface.  Then I have grayscaled the images and changed them to 100x100 scale. I have printed the number of data read and the number of available classes. I have calculated the number of images of each class and drawn a bar graph for it.

Finally, I have divided the dataset into two parts, train and test, with a suitable scale.
 
## Dataset
The [UIKFace](https://drive.google.com/file/d/0BxYys69jI14kYVM3aVhKS1VhRUk/view?resourcekey=0-dabpv_3J0C0cditpiAfhAw) dataset is a large-scale face dataset with a large age range from 0 to 116 years.  This dataset contains more than 20,000 face images along with the age, gender and race of each individual.  These images cover a great variety in facial pose, light, clarity, etc. This dataset is used for example for face recognition, age progression/age regression estimation, etc.

## Differnet Parameters Effect

In this project, I have checked the effect of different values of the following parameters on the network (by changing these parameters and re-running the relevant code section):

1. optimizer

2. epoch

3. Loss function

4. regularization
