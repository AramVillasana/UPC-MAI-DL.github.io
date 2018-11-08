---
permalink: /mlp-convnets-lab-autonomous/
---

The autonomous laboratory is open for your exploration. Using the basic code provided in the guided laboratory, students should modify it to test different settings, and understand the effect of the various components. You could use any dataset you wish. The list of datasets available at Keras can be found [here](https://keras.io/datasets/), but using one of those is not a requirement (dont use too simple datasets like MNIST). You can also use any framework you wish, train model you can find, or online dataset. In the end you must submit an 8 pages PDF document (references not included) with your work. Minimum font size of 11. In general, its better to focus in one aspect and to study it thoroughly, than to do small experiments on different topics without going any deep.

Upload your code to a publicly available site, e.g., github.

In this document there are a list of suggested questions you may consider to explore. It is not necessary to answer any or all these questions. The student may choose to perform different experiments, for explore different aspects of neural networks. Follow your own curiosity.

<a name='basic_nn'></a>
# Example 1: Basic NN

- What is the impact of using more fully connected layers?
- What is the impact of increasing the number of neurons per layer?
- What is the best performance you can get out of a basic neural net?



<a name='cnn'></a>
# CNN example

- Can you design and train a model that overfits on the training data (or on a subset of it)?
- When overfitting, what is the result of applying various regularization techniques?
- When using ReLUs, how many neurons are dead after a training?
- Adding data augmentation improves performance?
- How do the different learning algorithms behave for equal architectures? Does regularization have the same affect when using different algorithms?
- How hard is it to match the performance of an adaptative algorithm (e.g., Adam) by using an algorithm where parameters have to be hand tunned (e.g., SGD)?
- What is the result of using different weight initializations in the training process?


<a name='datasets'></a>
# Datasets
Follows a short list of freely available datasets to play with. You can find many more online.

- [mit67](http://web.mit.edu/torralba/www/indoor.html)
- [cub200](http://www.vision.caltech.edu/visipedia/CUB-200.html)
- [flowers102](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/)
- [sdogs](vision.stanford.edu/aditya86/StanfordDogs/)
- [caltech101](www.vision.caltech.edu/Image_Datasets/Caltech101/)
- [food101](www.vision.ee.ethz.ch/datasets_extra/food-101)
- [mit6i7](http://web.mit.edu/torralba/www/indoor.html)
- [textures](https://www.robots.ox.ac.uk/~vgg/data/dtd/)
- [wood](www.ee.oulu.fi/~olli/Projects/Lumber.Grading.html)

Choose this or other datasets depending on what you are trying to explore. Many/Few classes? Fine grained/General classes? Many/Few instances per class? Large/Small resolution?
If you think your study is independent of these variables, its good to validate such assumption by running experiments on more than one dataset.

<a name='tips'></a>
# Tips
Follows a list of tips for your report

- Properly introduce the data you work with
- Properly split the data into train, test and validation (if needed)
- Don't use datasets for which achieving a 95% of accuracy is straight-forward (NO MNIST)
- Use and show loss and/or accuracy plots in your discussion
- Apply techniques (e.g., regularization, data augmentation) for a reason and properly motivate it. Dont do it just for the sake of doing stuff.
- Use a number of neurons per layer which is a power of 2
- Dont try to use all possible methods and techniques. Focus on certain aspects, try to understand and interpret their behavior
- When using a plot, stare at it for a while. Try to reason what can be understood from it. Make yourself related questions and act in consequence. Write this process down in the report.
- To properly analyze and understand a model, train until overfit. Visualize both accuracy and loss curves.

# Original reports from previous courses
This is a list of interesting reports from previous years. Could serve as inspiration.

- Using an autoencoder to initialize the features of an image classifier, and comparison with typical initialization methods.

