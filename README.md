
<h1 align="center">Whats-the-number</h1>

## Description

Thanks to this project is combination of two areas: machine learning and web development. The whole application is written in React using TypeScript and Redux, but the engine that drives it is [TensorFlow.js][1] - a modern library for training and deploying machine learning models. 

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:3000
npm start
```

## MNIST

[MNIST][3] dataset is widely known in the field of machine learning. It contains about 70000 examples of handwritten digits. Photos are black and white, normalized to fit into a 28x28 pixel bounding box and anti-aliased. This iconic dataset was used to train the model in Keras and then turned into a form understandable to TensorFlow.js and used as the heart of the first project. The whole process of creating the model has been described in the [Medium][4] article.


## Build Keras models

If you are interested in neural networks and would like to know how to create models used in this project, I encourage you to test the scripts on your computer.

``` bash
# clone repository
git clone https://github.com/SkalskiP/ILearnMachineLearning.js.git

# navigate to models directory
cd ILearnMachineLearning.js/models

# install all required packages and dependencies as well as python environment
./setup.sh

# activate python environment
source .env/bin/activate
```
