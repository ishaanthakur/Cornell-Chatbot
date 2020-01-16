# Tensorflow Chatbot

Overview
============
 This is an implementation of Tensorflow's [Seq2Seq](https://www.tensorflow.org/versions/r0.12/tutorials/seq2seq/index.html) model to train a
chatbot on the [Cornell's Movie Dialogue dataset](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html). After training for couple of hours, the bot is capable of havinf fully functional conversation with the user.


Requirements
============
Use [pip](https://pypi.python.org/pypi/pip) to install following dependencies

* numpy
* scipy 
* tensorflow 




Usage
===========

To train the bot, edit the `seq2seq.ini` file as follows: -

`mode = train`

then run the following code in terminal

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file as follows:-

`mode = test`

then run the code like so

``python execute.py``



