# Transfer Learning Workshop

This workshop is designed to introduce you to the concept of transfer learning and how to use it to build a custom image classifier.

## Usage

```bash
git clone git@github.com:shangyuan191/TransferLearningDemo.git
cd TransferLearningDemo
```

```bash
pip install -r requirements.txt
```

Run the code in following order:

1. `simple_cnn.ipynb`
2. `transfer_learning_vgg16.ipynb`

## Dataset

Cat and Dog from Kaggle: https://www.kaggle.com/datasets/tongpython/cat-and-dog

| Cat                                | Dog                                |
| ---------------------------------- | ---------------------------------- |
| <img src=./src/cat.jpg height=200> | <img src=./src/dog.jpg height=200> |

## Simple CNN

We will start by building a simple Convolutional Neural Network (CNN) from scratch to classify images.

## Transfer Learning with VGG16

We will then use a pre-trained model, VGG16 from PyTorch, to build a custom image classifier.

## TODO

Finished TODO parts at transfer_learning_resnet34.ipynb
