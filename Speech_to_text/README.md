# Speech To Text

This folder contains all the code for Speech to text.
The implemtation has been done in two ways to compare the performance of each individual model sperately.

## Concept & Usage

First model is by using an LSTM recurrent Neural Network with CTC as the loss function.
The file named "lstm_ctc_model.py" contains all the code for the same. 

Second model is by using a dislated convolution neural network using CTC as the loss function.
The file named "dialated_convolution_ctc_model.py" contains all the code for the same.

"creatingdataset.py" is the script used for loading the wav file and correspoing txt (transcript) files and making a matrix used to feed into the model.

Note:- All the required files(wav, txt, etc) to be used should be placed properly in the directory as required by the code.
