# chatbot_danny_v10_appimage
Linux AppImage of Chatbot Danny version 1.0.7 made in freebasic

uses FLTK-C libraries which need to be copied to /usr/lib
can be found here:
https://www.freebasic.net/forum/viewtopic.php?t=24547

for TTS need to install espeak-ng
run in termial command: `sudo apt-get install espeak-ng`
and also install mbrola voives:
run in terminal command: `sudo apt-get install mbrola-voice-en`
and for the specific voice for chatbot danny need to install voice mborla-us2
run in terminal command: `sudo apt-get install mborla-us2`

appimage should be inside it's own folder
it creates log.txt file record of conversations
answers.txt and questions.txt files for learning new keywords and replies
if "LEARN MODE" is enabled
