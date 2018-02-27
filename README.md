# Speech Recognition and Sentiment Analysis Workshop

Presented at Data Science Münster, February 27, 2018

## Overview
Here is the code for speech recognition using Sphinx and Google cloud Speech API with input from micorphone. The text from speech recognition is then used as input to Google cloud Natural lagnguage API for sentiment analysis. We need a microphone to provide audio input to the program.

## Dependencies
- PyAdudio package
  - Install [PyAudio dependencies](https://people.csail.mit.edu/hubert/pyaudio/)
  - On Ubuntu, `sudo apt-get install portaudio19-dev`
  - `$ pip install pyaudio`
- Pocketsphinx package
  - `sudo apt-get install swig libpulse-dev`
  - `$ pip install pocketsphinx`  
- Speech recognition, `$ pip install SpeechRecognition`
- Install Google Speech API client, `$ pip install --upgrade google-cloud-speech`
- Install Google Natural Language API client, `$ pip install --upgrade google-cloud-language`
- [Authenticate Google Cloud ML API](https://cloud.google.com/natural-language/docs/quickstart-client-libraries#client-libraries-install-python)

## Usage
Run following code in the terminal,

`python speech_recognition_NL_processing.py`
