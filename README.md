# Neural_Networks

Neural networks are not a new method. The first artificial neural network was devised in 1943, but advances in computational power and speed have made them a much more viable strategy for solving complex problems over the last 5-10 years. Originally devised by mathmaticians and neuroscientists to illustrate the fundamental principles of how brains might work they lost favor in the second half of the 20th century only to surge in popularity in the 20-teens as software engineers used them to resolve mathmatically intractable problems. The application of neural networks to learning problems has been ongoing for 20 years, often to predict student behvior or to parse unstructured data such as student writing samples and provide natural sounding feedback through AI avatars.

In this project, we will use two datasets (attention1.csv and attention2.csv) to find data that describe features assocaited with webcam images of 100 students' faces as they particpate in an online discussion. 
* The variables are:
  * eyes - student has their eyes open (1 = yes, 0 = no)
  * face.forward - student is facing the camera (1 = yes, 0 = no)
  * chin.up - student's chin is raised above 45 degrees (1 = yes, 0 = no)
  * attention - whether the student was paying attention when asked (1 = yes, 0 = no)

We will use the webcam data to build a neural net to predict whether or not a student is attending.

## Packages Required
```
install.packages("neuralnet")
```

## Procedures

1. Upload the datasets.
2. Build a neural net that predicts attention based on webcam images.
3. Train the neural network by increasing the number of hidden layers in the neural net.
4. Create a new data frame that only includes the input layers to use this command.
5. Create predictions using the neural net.

## Author

[Meijuan Zeng](https://github.com/tomato018), MS student in Learning Analytics, Columbia University
