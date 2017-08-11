# machine-learning-class

## Machine Learning General

The following books are selected from [free-programming-books](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books.md#machine-learning)

- **[HTTP]** [A Course in Machine Learning](http://ciml.info/dl/v0_9/ciml-v0_9-all.pdf) (PDF)
- **[HTTP]** [A Brief Introduction to Neural Networks](http://www.dkriesel.com/en/science/neural_networks#a_brief_introduction_to_neural_networks)
- **[HTTP]** [Bayesian Reasoning and Machine Learning](http://www.cs.ucl.ac.uk/staff/d.barber/brml/)

## Perceptron

- [Single-layer Neural Networks (Perceptrons)](https://computing.dcu.ie/~humphrys/Notes/Neural/single.neural.html)
- [Single-Layer Neural Networks and Gradient Descent](https://sebastianraschka.com/Articles/2015_singlelayer_neurons.html)

- **[HTTP]** [Computing and the Brain](http://www.cs.stir.ac.uk/courses/ITNP4B/lectures/)
  - **[HTTP]** [Lecture 2: Single Layer Perceptrons](http://www.cs.stir.ac.uk/courses/ITNP4B/lectures/kms/2-Perceptrons.pdf) (PDF)
- **[HTTP]** [Introduction to Engineering Computation](http://www.cogconfluence.com/caam-210/)
  - **[HTTP]** [Single-layer Perceptron](http://www.cogconfluence.com/wp-content/uploads/2013/12/notes.pdf) (PDF)

- YouTube
  - [10: Neural Networks - The Nature of Code](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6aCibgK1PTWWu9by6XFdCfh) by The Coding Train

- Wikipedia
  - [Feedforward neural network - Wikipedia](https://en.wikipedia.org/wiki/Feedforward_neural_network)
  - [Perceptron - Wikipedia](https://en.wikipedia.org/wiki/Perceptron)

## Multilayer Neural Networks

- [Multilayer perceptron - Wikipedia](https://en.wikipedia.org/wiki/Multilayer_perceptron)
- [Backpropagation - Wikipedia](https://en.wikipedia.org/wiki/Backpropagation)
- [Gradient descent - Wikipedia](https://en.wikipedia.org/wiki/Gradient_descent)
- [Deep learning - Wikipedia](https://en.wikipedia.org/wiki/Deep_learning)


## A Neural Network Playground

http://playground.tensorflow.org

### Run it locally

1. Download playground
```shell
$ git clone https://github.com/tensorflow/playground.git
$ cd playground
$ git checkout tensor
```

2. Download [material icon fonts](https://github.com/lambda4fun/machine-learning-class/releases/download/material-icon-fonts/material-icon-fonts.zip) and extract it to `dist` directory.

3. Replace

`dist/index.html` - line 40
```css
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500|Material+Icons" rel="stylesheet" type="text/css">
```
to
```css
  <link href="fonts.css" rel="stylesheet" type="text/css">
 ```

4. Open `dist/index.html` in web browser.
