# CNN-MNIST-Digit-Recogniser
We are using CNN model to work on MNIST Dataset

CODE EXPLANATION:

MNIST:- This ipynb file consist of a CNN implemented dirctly. 

MNIST_DETAILED:-This ipynb file is divided into many subparts:

1)In first step I have implemented a linear model(flatten and dense) which has given me a accuracy of 90%. 

2)I have included a RELU activation function in the earlier linear model thus creating a FC layer which improved my accuracy to 95%.

3)Next step is to create a full CNN network containing Conv2D, maxpooling ,flatten and dense layer thus increaing accuracy by 2% more leading to 97%.

4)In the next step I have tried Data augmentation but no improvement observed may be as we already have 42000 images in total. Further increasing is not helping the model.

5)Batch Normalization has been used in next step increasing the accuracy to 98%.

6)Dropout has been tried but the accuracy remained same at 98%.


Competition Description
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.

Practice Skills
Computer vision fundamentals including simple neural networks

Classification methods such as SVM and K-nearest neighbors

Acknowledgements 
More details about the dataset, including algorithms that have been tried on it and their levels of success, can be found at http://yann.lecun.com/exdb/mnist/index.html. The dataset is made available under a Creative Commons Attribution-Share Alike 3.0 license.


