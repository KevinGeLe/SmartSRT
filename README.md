# SmartSRT
SmartSRT is my attempt, at an community run end-to-end solution for automatically generating subtitles for videos with a maximum subtitle length constraint, along with speaker diarization. It uses machine learning models for speech recognition, text summarization, face regocnition, and diarization, and will run on a CUDA GPU for faster performance.
<p align="center">
  <img src="https://user-images.githubusercontent.com/125448701/219095732-20b727b8-8f3f-4f06-a89b-ab43faf3a7e7.png" alt="Your image">
</p>
# Getting Started
You need to install the required dependencies and download the necessary models.\
⚠️Remember that you have to use a CUDA supported GPU!⚠️

Clone the repository:\
`git clone https://github.com/KevinGeLe/SmartSRT.git`\
Install the required dependencies:\
`cd SmartSRT`\
`pip install -r requirements.txt`\
The necessary models will be downloaded, by specifying the models that you want to use.


# TODO:
- [ ] Add Face recognition (±1 second)👱
- [ ] Add Max-Subtitle-Lenght with Per-Word-Timestamps:🕰️
- [ ] Add new parsers for Max-Lenght, Output, Input and Model🔍
- [x] Refactor code to improve readability🐊
- [ ] Work on improving performance🦈
- [ ] Update README.md📑


# License
SmartSRT is released under the MIT license. See the LICENSE file for more information.
