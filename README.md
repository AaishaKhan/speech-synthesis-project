# speech-synthesis-project
![istockphoto-1154653785-612x612](https://github.com/AaishaKhan/speech-synthesis-project/assets/65846423/6ecbf392-e1bf-41b2-9529-cc158e90885f)


## Introduction
This project is aimed at performing speech synthesis tasks, including speech-to-text (English), translation to Hindi, and text-to-speech (Hindi) functionalities. The goal is to generate speech that resembles a target speaker's natural voice, copy the accent of the original audio, and provide options for generating speech at different speeds and pitches.

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Requirements
- Python 3.x (tested with Python 3.8)
- Required Python libraries:
  - speech_recognition
  - googletrans==3.1.0a0
  - gtts
![istockphoto-165840818-612x612](https://github.com/AaishaKhan/speech-synthesis-project/assets/65846423/cfa1133b-f289-451c-914b-ae70ea3dbc75)

## Installation
1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/speech-synthesis-project.git


1.Install the required Python libraries using pip:
pip install SpeechRecognition
pip install googletrans==3.1.0a0
pip install gTTS

Usage
1. Speech-to-Text (English):

To convert an English audio file to text, use the speech_to_text function with the path to the audio file as an argument.
from speech_processing import speech_to_text

english_audio_file_path = "path/to/english_audio.wav"
english_text = speech_to_text(english_audio_file_path)
print("English Text:", english_text)

2. Translation to Hindi:

Use the translate_to_hindi function to translate English text to Hindi.
from speech_processing import translate_to_hindi

english_text = "Your English text here"
hindi_text = translate_to_hindi(english_text)
print("Hindi Text:", hindi_text)

3.Text-to-Speech (Hindi):

Convert Hindi text to speech and save the audio file using the text_to_speech_hindi function.
from speech_processing import text_to_speech_hindi

hindi_text = "Your Hindi text here"
hindi_audio_output_file_path = "output_hindi.mp3"
text_to_speech_hindi(hindi_text, hindi_audio_output_file_path)



Contributing
If you want to contribute to this project, you're welcome to open issues or submit pull requests. Any suggestions, bug reports, or feature requests are highly appreciated.


License
This project is licensed under the MIT License 
