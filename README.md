# SpeechToText

###Speech-to-Text Conversion Model


This repository contains a speech-to-text conversion model that leverages the Word2Vec algorithm to convert spoken language into written text. The model is designed to handle various accents(like Indian Accents,etc.) and noise levels, making it robust for real-world applications. It is implemented in Python and is suitable for use in voice assistants, transcription services, and other speech recognition systems.

###Installation
To install the necessary dependencies and set up the environment, follow these steps:

Clone the repository:
git clone https://github.com/mohnishraj22/SpeechToText.git
cd SpeechToText


Create and activate a virtual environment (optional but recommended):
python3 -m venv venv
cd venv\Scripts\activate

Install the required dependencies:
pip install -r requirements.txt

###Dataset

Nptel pure data of used in this model.
https://github.com/AI4Bharat/NPTEL2020-Indian-English-Speech-Dataset

###Results

####Average Character Error Rate (ACER) :-  0.1681

#####Examples
1)
Audio File: 000a5ab9a25b36037d8f1fd2df1885d34fb23df124e714400229dddf.wav
Reference: OF VELOCITY IN THIS DIRECTION IMAGINE THE SHIP THE SECTIONS ARE VERY THIN HERE<br>
Transcription: OF VELOCITY IN THIS DIRECTION IMAGINE THE SHIPTHE SECTIONS ARE VERY THIN HERE<br>
CER: 0.0128

2)
Audio File: 000a5d6898002138b2d74785c044b87b80c478407e8438ff7f425227.wav
Reference: SO ONE SHOULD BE KNOWLEDGEABLE IN THAT AND THEN THEY SHOULD SUPERVISE PROPERLY THEN SAMPLE<br>
Transcription: OUGH ONE SHOULD BE KNOWLEDGEABLE IN THAT D THEY SHOULD SUPERVISE PROPERTHE SM<br>
CER: 0.2111





