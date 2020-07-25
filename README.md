<a href="https://colab.research.google.com/drive/11eY1TOrUpQAcsN0qKqbflFh-Q_r6OQ4A?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
# Handwriting-recognition
#### MNIST database is a dataset of 60,000 small square greyscale with 28x28 with an image of handwritten digits from 0 to 9, our motto is to classify the digit input in the drawing padof Gradio interface.
- #### MNIST is widely used to classify the digits and the accuracy varies from 99% ± 0.2-0.4%, below is the example to show the plot for the MNIST dataset. 
- #### this shows the images used in the training set the 28x28 pixels are flattened into a 1D vector which is 784 pixels in size. Each of the 784 pixels making up the image is stored as a value between 0 and 255. 
- #### This determines the grayscale of the pixel, as our images are presented in black and white only. So a black pixel is represented by 255, and a white pixel by 0, with the various shades of gray somewhere in between.
Live Demo: https://27203.gradio.app/

### *ReLU (Rectified Linear Unit): ReLU stands for rectified linear unit, and is a type of activation function. Mathematically, it is defined as*
$f(x)=max(0,x)$ 

### Softmax Activation Function: ### It is an activation function that turns numbers aka logits into probabilities that sum to one. Softmax function outputs a vector that represents the probability distributions of a list of potential outcomes.
##### The softmax function is another type of AF used in neural networks to compute probability distribution from a vector of real numbers. This function generates an output that ranges between values 0 and 1 and with the sum of the probabilities being equal to 1. The softmax function is represented as follows:
