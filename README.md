# First-Responders-Mental-Health
Georgia Tech Sonification Lab

ModelSave.py - this is the file that contains the code for creating and training the neural net using the ryerson audio and visual dataset

In order to run the speech emotion recognition program you need to run python3 Modelsave.py from your command terminal. There are some dependencies that must first be installed before running this program. Simply run this line from your terminal:
pip3 install librosa==0.6.3 numpy soundfile==0.9.0 sklearn pyaudio==0.2.11

CustomSpeecRecognition.py - this file is the code for recording a custom recording of your/ another persons voice then running that recording through the trained machine learning model. The program will then classify your voice as one of 8 emotions coded into the machine learning model.
To run your voice through the model simply run python3 CustomSpeecRecognition.py after having run python3 Modelsave.py from your command terminal.


