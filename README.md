# REKOR - An Automated Voice Recognition Application 

This application is a real-time speech-to-text transcription tool that utilizes the Whisper-1 API model for smart transcription and the Translatepy library for translation, which will eventually be added later as I work on this. Whisper enables efficient speech transcription as well as speech recognition even on devices with 6GB or less VRAM. Multiple changes including speech recognition and visual changes to the transcription window will be pushed in the coming days. A wide range of customizations including the desired language of transcription, choosing the model, and microphone options will also be available soon.

Installation
To install the necessary dependencies, follow these steps:

Open your preferred environment and run the following command:
Copy code
pip install -r requirements.txt
Additionally, Whisper requires the command-line tool ffmpeg to be installed on your system. Below are the installation instructions for different operating systems:
Ubuntu or Debian:
bash
Copy code
sudo apt update && sudo apt install ffmpeg
Arch Linux:
bash
Copy code
sudo pacman -S ffmpeg
MacOS using Homebrew:
bash
Copy code
brew install ffmpeg
Windows using Chocolatey:
bash
Copy code
choco install ffmpeg
Windows using Scoop:
bash
Copy code
scoop install ffmpeg
For more information about Whisper, please refer to the official repository: https://github.com/openai/whisper

Acknowledgement
This application was developed with the implementation of the whisper_real_time library.

Contribution
This project is open-source and falls under the public domain. Contributions from the community are welcome and appreciated. Feel free to fork the repository and submit pull requests to help enhance the functionality and features of REKOR.

Disclaimer
Please note that the Whisper-1 API model and the Translatepy library are subject to their respective licenses, and users are responsible for complying with those terms. The developers of REKOR are not liable for any misuse or violation of third-party licenses. Use the application responsibly and ensure you have the necessary rights to use the included technologies.

For any inquiries or support, please reach out to the project maintainers. Happy transcribing with REKOR!



 
