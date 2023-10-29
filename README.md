# SignatureVerification
Problem Statement:- Given two signatures, return a probablity or a label indicating that the two signatures are matching are not.
The problem was initially posted in kaggle.com under signature verification datasets.

Solution to this problem required implementation of siamese network.
<h3>Siamese Networks</h3>
<p>
  Siamese networks are a type of neural network architecture designed for tasks involving similarity or distance measurements between pairs of input data. These networks are particularly used in tasks such as image or signature verification, face recognition, and similarity-based classification.</p>
  <p>
    Twin Networks:
A Siamese network consists of two identical subnetworks (twins) that share the same architecture and parameters. These twins are typically convolutional neural networks (CNNs) in computer vision applications.</p>
<p>
  Shared Weights:
The weights and biases of the twin networks are tied, meaning they are the same for both networks. This is a crucial aspect of Siamese networks, as it enforces the networks to learn similar features from the input data.
  <p>
    Pairwise Input:
Siamese networks take pairs of input data during training and learning. Each input pair consists of two instances, and the goal is to train the network to understand the similarity or dissimilarity between these pairs.
  </p>

<p>
  Contrastive Loss:
The training of Siamese networks often involves a contrastive loss function. This loss function encourages the network to minimize the distance between similar pairs and maximize the distance between dissimilar pairs. The distance can be measured using various metrics, such as Euclidean distance or cosine similarity.
Applications:
</p>
<p>
  Similarity Measurement:
Siamese networks are commonly used in tasks where the goal is to measure the similarity or dissimilarity between pairs of data points. This can include face verification, signature verification, and more.
</p>
<p>
  One-Shot Learning:
Siamese networks are suitable for one-shot learning scenarios where you have limited labeled examples. The network can be trained to recognize new instances by comparing them to a few examples of known instances.
</p>




