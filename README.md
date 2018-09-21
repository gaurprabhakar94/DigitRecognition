# DigitRecognition
Recognizes hand written digits using two methods -- by training a model trained in tensorflow on the MNIST dataset and by training a support vectore classifier model on UCI’s Optical Recognition of Handwritten Digits Data Set.

After training the model in Tensorflow, to see what is happening under the hood we visualize the model weights using seismic maps. The classifier makes its prediction by comparing how similar or different the digit is to the red and blue. Consider the colors as-- darker the red, the better of a hit; white as neutral; and blue as misses.

After training the SVC model, we fine tune the parameters to get a high accuracy that beats the advertised stats by the United States Postal Service stats.














Special thanks to O'reilly and Justin Francis for creating wonderful content. They really helped me understand the basics of Tensorflow.
https://www.oreilly.com/learning/not-another-mnist-tutorial-with-tensorflow 
