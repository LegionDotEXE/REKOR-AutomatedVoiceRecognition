# REKOR - An Automated Voice Recognition Application 

This application is a real-time speech-to-text transcription tool that utilizes the Whisper-1 API model for smart transcription and the Translatepy library for translation, which will eventually be added later as I work on this. Whisper enables efficient speech transcription as well as speech recognition even on devices with 6GB or less VRAM. Multiple changes including speech recognition and visual changes to the transcription window will be pushed in the coming days. A wide range of customizations including the desired language of transcription, choosing the model, and microphone options will also be available soon.

# INSTALLATION

To install the dependencies, simply run:
pip install -r requirements.txt

Whisper also requires the command-line tool ffmpeg to be installed on your system:

# on Ubuntu or Debian
sudo apt update && sudo apt install ffmpeg

# on Arch Linux
sudo pacman -S ffmpeg

# on MacOS using Homebrew (https://brew.sh/)
brew install ffmpeg

# on Windows using Chocolatey (https://chocolatey.org/)
choco install ffmpeg

# on Windows using Scoop (https://scoop.sh/)
scoop install ffmpeg
For more information on Whisper please see https://github.com/openai/whisper

The code in this repository is public domain.

# ACKNOWLEDGEMENT
This application was created with the implementation of the [whisper_real_time](https://github.com/davabase/whisper_real_time)



 
