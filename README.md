# Mechanistic Interpretability Challenge

## (SOLVED) Challenge 1, MNIST CNN:

Solution report: [Solving the Mechanistic Interpretability challenges: EIS VII Challenge 1](https://www.alignmentforum.org/posts/sTe78dNJDGywu9Dz6/solving-the-mechanistic-interpretability-challenges-eis-vii) 

Use mechanistic interpretability tools to reverse engineer an MNIST CNN and send me a program for the labeling function it was trained on. 

Hint 1: The labels are binary.

Hint 2: The network gets 95.58% accuracy on the test set. 

Hint 3: The labeling function can be described in words in one sentence.

Hint 4: This image may be helpful. 

![mnist example](figs/mnist_example.png)

MNIST CNN challenge:  [![MNIST CNN challenge -- Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15ByJYkksF9Bxb0rVkaoIZbUEWtbBDDqN?usp=sharing)

## (Solved) Challenge 2, Transformer:

As of May 9, 2023, this challenge has been solved. A link to the report from those who solved it is forthcoming. 

Use mechanistic interpretability tools to reverse engineer a transformer and send me a program for the labeling function it was trained on. 

Hint 1: The labels are binary.

Hint 2: The network is trained on 50% of examples and gets 97.27% accuracy on the test half. 

Hint 3: Here are the ground truth and learned labels. Notice how the mistakes the network makes are all near curvy parts of the decision boundary...

<img src="figs/transformer_labeling_function.png" alt="drawing" width="400"/>

Transformer challenge:  [![MNIST CNN challenge -- Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19gn2tavBGDqOYHLatjSROhABBD5O_JyZ?usp=sharing)

## Rewards:

If you send me code for one of the two labeling functions along with a justified mechanisic interpretability explanation for it (e.g. in the form of a colab notebook), the prize is a $750 donation to a high-impact charity of your choice. So the total prize pool is $1,500 for both challenges. Thanks for Neel Nanda for contributing $500!
