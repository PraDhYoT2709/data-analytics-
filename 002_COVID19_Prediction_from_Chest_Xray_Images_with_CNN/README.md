

# Prediction of COVID-19 from Chest X-ray Images with CNN (Convolutional Neural Network)

In this project, Built and trained a convolutional neural network in Keras with TensorFlow as backend from scratch to predict patients if they were infected with COVID-19 or not using their chest X-ray images. 
Matplotlib was used for data visualization. Data preprocessing and data augmentation was carried out using tensorflow 2.0
The model used was sequential with a combination of convolutional layers, pooling layers, dropout layers, dense layers with relu activation and output layer with sigmoid activation.  The dataset contained the lungs X-ray images of both groups i.e non-covid and covid infected patients. The dataset was obtained from kaggle. Metrics chosen for model evaluation were Training set, test set and validation set accuracy. Adam optimizer with learning rate of 0.001 was choosed for gradient descent
The entire project was carried out on the Google Colab environment
Results of the model were following:

1) Training Set Accuracy : 98.41 %
2) Training Set Loss : 0.0490

3) Validation Set Accuracy : 97.51 %
4) Validation Set Loss: 0.0759

5) Test Set Accuracy : 94.83 %
6) Test Set Loss : 0.1141

Google Colab Project Link : https://colab.research.google.com/drive/1oeA2Rp5B_8VWtOXEoY7R4dQMaO4pZe_y?usp=sharing

![image](https://user-images.githubusercontent.com/77073932/128634391-9ea593fd-87c6-4646-88d6-573adeb3b6a5.png)


---


## Install Necessary Modules:

Open your [![Anaconda](https://img.shields.io/badge/Anaconda-342B029.svg?&style=flate&logo=anaconda&logoColor=white)](https://www.anaconda.com/products/individual) Prompt <img alt="propmt" src="https://img.shields.io/badge/-__-000000?style=flat-square&logo=Plex&logoColor=white"> and type and run the following command (individually):

 -       pip install pandas
       
 -       pip install numpy  
  
 -       pip install tensorflow

Once Installed now we can import it inside our python code.

---

