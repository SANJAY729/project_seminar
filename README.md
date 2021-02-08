# project_seminar
how to run
open in colab and run (GAN_sincurve, GAN_handwrittendigits) - no need any input file

LSTM_textgen requires aliceinwonderland text file as input text. For training need to run till cell 7.
It will save weights learnt in each epoch. In code cell 8 have to change the input weights to the one 
generated in code cell 7 if training again. Training takes about 5 min. If not training then can use pre
computed weights "weights-improvement-20-1.9410.hdf5". (skip cell 6,7 if not training)

LSTM2_textgen requires aliceinwonderland text file as input text. For training need to run till cell 7.
It will save weights learnt in each epoch. In code cell 8 have to change the input weights to the one 
generated in code cell 7 if training again. Training takes about 1hr. If not training then can use pre
computed weights "weights-improvement-39-1.2592.hdf5". (skip cell 6,7 if not training)

GAN_handwrittendigits is not working as intended although the code is similar to GAN_sincurve and sincurve is 
working.
