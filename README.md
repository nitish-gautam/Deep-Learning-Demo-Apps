# Deep-Learning-Demo-Apps
The intention here is to create a generic repositories which contain various practical applications in the field of deep learning.

### Dependencies
<ul>
    <li> 
        <a href="https://www.tensorflow.org/guide/keras" >Keras</a>
    </li>
</ul>

### PRACTICAL DEMO APPLICATION PROJECTS
PROJECT 1. IMAGE CLASSIFICATION (MNIST-10) USING CNNs - APPLICATION

PROJECT 2. IMAGE CLASSIFICATION (CIFAR-10) USING CNNs - APPLICATION

PROJECT 3. CLASSIFY GERMAN TRAFFIC SIGNS (LENET) USING CNNs - APPLICATION

PROJECT 4. CLASSIFY FASHION IMAGES(FASHION-MNIST) USING CNNs - APPLICATION

PROJECT 5. CLASSIFY CUSTOM IMAGE CLASSIFICATION -APPLICATION

-----------------------------------------------------------------------------------------------------------------------------------
### PROJECT 1. IMAGE CLASSIFICATION (MNIST-10) USING CNNs - APPLICATION
The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. The digits have been size-normalized and centered in a fixed-size image. It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9. The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively.

```
     https://en.wikipedia.org/wiki/MNIST_database
     DATASET : http://yann.lecun.com/exdb/mnist/  
     
```

### RESULT AND SUMMARY: 
(A) Model Summary, Confusion Matrix and  Prediction vs Actual reporting
![Mnist-Img](https://user-images.githubusercontent.com/46977634/71091667-6e293d80-219d-11ea-9805-996e8e950b12.JPG)
![Mnist-Predict_vx_Actual](https://user-images.githubusercontent.com/46977634/71091928-0aebdb00-219e-11ea-86dc-43e801678f36.JPG)

-----------------------------------------------------------------------------------------------------------------------------------
### PROJECT 2. IMAGE CLASSIFICATION (CIFAR-10) USING CNNs - APPLICATION
CIFAR-10 is a dataset that consists of several images divided into the following 10 classes:
0: Airplanes  1: Cars  2: Birds  3: Cats  4: Deer  5: Dogs  6: Frogs  7: Horses  8: Ships  9: Trucks 

The dataset stands for the Canadian Institute For Advanced Research (CIFAR) CIFAR-10 is widely used for machine learning and computer vision applications. The dataset consists of 50,000 32x32 color training images, labeled over 10 categories, and 10,000 test images.

```
DATASET: https://www.kaggle.com/c/cifar-10/   or https://www.cs.toronto.edu/~kriz/cifar.html
```

### RESULT AND SUMMARY: 
(A) Model Summary, confusion Metrix and Prediction vs Actual reporting
![image](https://user-images.githubusercontent.com/46977634/76878980-8298d700-686d-11ea-99f2-681bcb60261f.png)
![image](https://user-images.githubusercontent.com/46977634/76879038-96443d80-686d-11ea-96f5-70ee8e122a16.png)
![image](https://user-images.githubusercontent.com/46977634/76879096-a9efa400-686d-11ea-9130-4159b737c7b0.png)
![image](https://user-images.githubusercontent.com/46977634/76879134-b673fc80-686d-11ea-819c-af9da65be07b.png)
![Capture](https://user-images.githubusercontent.com/46977634/76879312-fdfa8880-686d-11ea-9959-bad7980f65bb.JPG) 

-----------------------------------------------------------------------------------------------------------------------------------
### PROJECT 3. CLASSIFY GERMAN TRAFFIC SIGNS (LENET) USING CNNs - APPLICATION
•	The dataset contains 43 different classes of images. Classes are as listed below:
•	( 0, b'Speed limit (20km/h)') ( 1, b'Speed limit (30km/h)')
•	( 2, b'Speed limit (50km/h)') ( 3, b'Speed limit (60km/h)')
•	( 4, b'Speed limit (70km/h)') ( 5, b'Speed limit (80km/h)')
•	( 6, b'End of speed limit (80km/h)') ( 7, b'Speed limit (100km/h)')
•	( 8, b'Speed limit (120km/h)') ( 9, b'No passing')
•	(10, b'No passing for vehicles over 3.5 metric tons')
•	(11, b'Right-of-way at the next intersection') (12, b'Priority road')
•	(13, b'Yield') (14, b'Stop') (15, b'No vehicles')
•	(16, b'Vehicles over 3.5 metric tons prohibited') (17, b'No entry')
•	(18, b'General caution') (19, b'Dangerous curve to the left')
•	(20, b'Dangerous curve to the right') (21, b'Double curve')
•	(22, b'Bumpy road') (23, b'Slippery road')
•	(24, b'Road narrows on the right') (25, b'Road work')
•	(26, b'Traffic signals') (27, b'Pedestrians') (28, b'Children crossing')
•	(29, b'Bicycles crossing') (30, b'Beware of ice/snow')
•	(31, b'Wild animals crossing')
•	(32, b'End of all speed and passing limits') (33, b'Turn right ahead')
•	(34, b'Turn left ahead') (35, b'Ahead only') (36, b'Go straight or right')
•	(37, b'Go straight or left') (38, b'Keep right') (39, b'Keep left')
•	(40, b'Roundabout mandatory') (41, b'End of no passing')
•	(42, b'End of no passing by vehicles over 3.5 metric tons')
The network used is called Le-Net that was presented by Yann LeCun 
```
http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf
```

### RESULT AND SUMMARY: 
(A) Model Summary, confusion Metrix and Prediction vs Actual reporting
![image](https://user-images.githubusercontent.com/46977634/76879633-6cd7e180-686e-11ea-966d-b2a8a7f47d45.png)
![image](https://user-images.githubusercontent.com/46977634/76879588-5cc00200-686e-11ea-8476-409e422595f7.png)
![image](https://user-images.githubusercontent.com/46977634/76879502-40bc6080-686e-11ea-979d-fc800bbc3e2b.png)


![LENET-CM-Img](https://user-images.githubusercontent.com/46977634/71091924-09221780-219e-11ea-8515-1ca59788d7a9.JPG)

-----------------------------------------------------------------------------------------------------------------------------------
### PROJECT 4. CLASSIFY FASHION IMAGES (FASHION-MNIST) USING CNNs - APPLICATION
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

Each training and test example is assigned to one of the following labels:

0 T-shirt/top
1 Trouser
2 Pullover
3 Dress
4 Coat
5 Sandal
6 Shirt
7 Sneaker
8 Bag
9 Ankle boot

```
DATASET: https://github.com/zalandoresearch/fashion-mnist
DATASET was converted to CSV with this script: https://pjreddie.com/projects/mnist-in-csv/
```


### RESULT AND SUMMARY: 
![image](https://user-images.githubusercontent.com/46977634/77553722-13defd80-6ead-11ea-8e79-6d71e073a268.png)
![image](https://user-images.githubusercontent.com/46977634/77554004-6f10f000-6ead-11ea-8eec-e5fd799f803b.png)
![image](https://user-images.githubusercontent.com/46977634/77553968-615b6a80-6ead-11ea-8934-73b1094df436.png)

### PROJECT 5. CLASSIFY CUSTOM IMAGE USING CNNs - APPLICATION
The intention here is to create a generic custom image classifier which can be used with any real world custom image classification.

![image](https://user-images.githubusercontent.com/46977634/80416440-082b9000-88cc-11ea-85e1-b8e51543f926.png)
