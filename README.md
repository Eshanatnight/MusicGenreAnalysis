# Music Genere Classification

Audio Classification is an Application of Machine Learning where different sound is categorized into certain categories. In our case we will be subclassifying the music into different genres.

I want to build a complete *music Genre classification* project from scratch using a machine learning algorithm known as the **K-Nearest Neighbors classification algorithm**.

We are using the **K-Nearest Neighbors** algorithm beacause of loads of reasons, one of them being I just learned it and I want to use it in the real world.

## Project Overview

In short, we can define our project *problem statement* as like

```Given multiple audio files, and the task is to categorize each audio file in a certain category like audio belongs to Disco, hip-hop, etc. The music genre classification can be built using different approaches ```

in which the top 4 most used approaches are listed below.

* Multiclass Support Vector Machine

* K-Nearest Neighbors

* K-means Clustering Algorithm

* Convolutional Neural Network

**K-Nearest Neighbour**: is a machine learning algorithm used for regression, and classification. It is also known as the lazy learner algorithm. It simply uses a distance-based method to find the K number of similar neighbours to new data and the class in which the majority of neighbours lies, it results in that class as an output.

**Convolutional Neural Network**: is a type of deep learning algorithm that is used to classify images. It is a type of neural network that is used to classify images, natural language, and other similar data.

## Dataset overview

The dataset we will use is named the **GTZAN genre collection dataset** which is a very popular audio collection dataset. It contains approximately 1000 audio files that belong to 10 different classes. Each audio file is in ```.wav``` format.

The classes to which audio files belong are *Blues, Hip-hop, classical, pop, Disco, Country, Metal, Jazz, Reggae, and Rock*.

Available On Kaggle: [dataset](https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification?select=Data)

## Results

In boths ways, we are accurate upto 70% of the time. Classification is having trouble with the *pop* and *rock* genres especially, often misclassifying the *rock* genre as *pop* and vice versa. But the again both of the music genre sound somewhat similar. Really wanted it to be a bit more accurate but a success is a success nonetheless.
