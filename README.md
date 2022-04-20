# MachineLearning_and_ImageProcessing
Logistic Regression model built in order to identify if image is real or fake, including properties extraction algorithm

In this project we implement a Logistic Regression classification with Gradient Descent model in order to identify if image is real or fake.
We used a database that contains 1000 images and divided into 500 'Real' images and 500 'Fake' images, in order to implement the machine learning model
we needed to extract suitable properties.

The first part is the Image Proccesing part.
In this part we read the images from the currect folders into a matrix, than we extract some properties from the images (including FFT, Azimuthal Average and more)
and saved them for the second part.

The second part is the Machine Learning part.
In this part we implement a Logistic Regression classification with gradient descent from scratch and used him in order to create a regressor.

For the gradient descent we nedded to choose the best alpha and w0 
while creating the regressor we needed to choose the best combination of alpha and w0.
        <img width="294" alt="image" src="https://user-images.githubusercontent.com/88097271/164233610-a0127445-c4e4-49f7-8936-9c6ec59a2552.png">

For maximum performance in a small number of steps we have created a graphes that will help us decide :

<img width="860" alt="image" src="https://user-images.githubusercontent.com/88097271/164234188-7422beb7-cdb0-4e87-aa90-e1b001a7dce1.png"><img width="857" alt="image" src="https://user-images.githubusercontent.com/88097271/164234246-50a15d7a-9e02-4430-aaed-009549e3b3bb.png">

finally we have used this regressor to identify which images are real and which images are fake.
