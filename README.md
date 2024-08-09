Converting text input to speech given the input language 
# Whisper TTS model

This project uses WhisperSpeech to convert text to speech, with an option for voice cloning.
reference - https://github.com/collabora/WhisperSpeech

## Setup and Installation

1. Create and activate a virtual environment:
    - Linux
        - python -m venv venv
        - source venv/bin/activate
    - Windows
        - python -m venv venv
        - venv\Scripts\activate

2. Install the required packages:
    - ```bash
        pip install -r requirements.txt
        ```
3.  Usage

    You can add the reference audio from a drive download link to create a more personalized transcriptions or a  pass a direct audio file path.
    - voice with cloning

        <audio controls src="output_with_cloning.mp3" title="Title"></audio>
    
    - output without cloning
        
        <audio controls src="output_without_cloning.mp3" title="Title"></audio>