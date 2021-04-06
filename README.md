# Kaplan Meier Plot Classifier

* This code repo consists of 3 models used to classify plots as being either Kaplan Meier plots, or not. The three models are:
  * **Bag of Words** - Pytesseract uses Optical Character Recognition to extract words from an image, and uses a bag of words machine learning model to predict the probability that the image contains a Kaplan Meiers plot.
  * **Fastai Deep Learning** - A convolutional neural net image classifier, fine tuned from the existing resnet152 model.
  * **Ensemble model** - an average of the probabilities output from the above two models, and shows to be the highest performing.
* The code in this repo is a work in progress and hasn't been optimised to run on other machines yet.


## Usage

To-do

## Contributing
The current contributor(s) to this project are:
* Sam Bradley