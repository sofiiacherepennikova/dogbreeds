# Dog Breeds Classifier

This repository contains a dog breeds classifier implemented using a Convolutional Neural Network (CNN) on a dataset of 9813 dog breed images. The classifier is trained to predict the breed of a dog given an image as input.

## Dataset

The dataset used for training and testing the classifier consists of 9813 images of various dog breeds. Each image is labeled with the corresponding breed of the dog.

## Model

The classifier is implemented using a CNN architecture, which is a type of deep neural network commonly used for image classification tasks. The model is trained on the dataset using the PyTorch framework.

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

4. Train the classifier by running the `train.py` script:

```
python train.py
```

5. Test the classifier on a sample image by running the `predict.py` script:

```
python predict.py path/to/sample/image.jpg
```

## Results

After training the classifier on the dataset, it achieved an accuracy of X% on the test set. The model is able to correctly classify the breed of a dog in the sample image with a confidence score of Y%.

## Credits

The dataset used for this project is sourced from [XYZ](link-to-dataset).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
