# Dog Breeds Classifier

This repository contains a dog breeds classifier implemented using a Convolutional Neural Network (CNN) on a dataset of 9813 dog breed images. The classifier is trained to predict the breed of a dog given an image as input.

## Dataset

The dataset used for training and testing the classifier consists of 9813 images of various dog breeds downloaded from https://www.kaggle.com/datasets/gpiosenka/70-dog-breedsimage-data-set . Each image is labeled with the corresponding breed of the dog.

## Model

It consists of multiple convolutional layers followed by max pooling layers to extract features from the input images. The model then flattens the output and passes it through several dense layers with dropout regularization to classify the images into different classes. The model uses the Adam optimizer with a learning rate of 0.0001 and categorical crossentropy as the loss function.

## Usage

To use the classifier, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/dog-breeds-classifier.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Download the dataset and place it in the `data` directory.

5. Test the classifier on a sample image by running the `predict.py` script:

## Results

After training the classifier on the dataset (20 epochs), it achieved an accuracy of 72.5% on the test set.
Note! Only few breeds were selected of all 70 due to lack of the computational power. Training took approximately 60 mins of Apple M1 Pro chip.

## Bonus

I have an amazing dog of a very rare breed. It is Japanese Hokkaido (Ainu) dog. If I were payed everytime I am asked by the strangers, what is the breed of this "cuuutie", I would.. you know. I could also provide the statistics of common breeds confused with Yuki's. The top is (definitely) white Shiba, then Laika and sometimes a puppy of Akita. 
This breed has hardly 5000 of representatives around the world, so this would be hard to add them to any sort of dataset (even small). 

Anyway, the model agreed with the majority of people met by us in the street:

  ![Yuki]([image URL](https://github.com/sofiiacherepennikova/dogbreeds/blob/main/yuki_1.jpg?raw=true))

