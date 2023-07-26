# REKOR - AN AUTOMATED SPEECH RECOGNITION APPLICATION

REKOR is a real-time speech-to-text transcription tool that utilizes the Whisper-1 API model for smart transcription and the Translatepy library for translation (which will be added later in the development). The Whisper API enables efficient speech transcription and recognition even on devices with 6GB or less VRAM. In the coming days, we have planned multiple changes, including improvements in speech recognition and visual updates to the transcription window. Additionally, we will be introducing a wide range of customizations, such as selecting the desired language for transcription, choosing different models, and providing microphone options.

# INSTALLATION
To install dependencies simply run
```
pip install -r requirements.txt
```
in an environment of your choosing.

Whisper also requires the command-line tool [`ffmpeg`](https://ffmpeg.org/) to be installed on your system. Please refer to the code based on your system.

```
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
```

For more information on Whisper please see https://github.com/openai/whisper

The code in this repository is public domain.

# ACKNOWLEDGEMENT
This application was created with the implementation of the [whisper_real_time](https://github.com/davabase/whisper_real_time/tree/master) library, and we express our gratitude to its developers for their valuable contribution.

# CONTRIBUTION
For any questions, suggestions, or collaborations, please do contact. 



Thank you for using REKOR! We hope this automated voice recognition application enhances your transcription experience.
# CONTRIBUTING
We welcome contributions from the community. If you find any issues or have ideas for improvements, please feel free to open an issue or create a pull request.

