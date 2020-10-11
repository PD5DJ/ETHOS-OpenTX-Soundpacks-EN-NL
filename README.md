# OpenTX Soundpacks EN & NL
 OpenTX TTS Automate EN & NL Soundpacks

----------------------------------------------------------------

Small writeup how to Create OpenTX soundpacks with TTS Automate and Batch edit the audio files with Audacity.


**TTS Automate**
----------------------------
OpenTX is provided with the possibility to use sound packs.

These are audio (wav) files, and you can play these from OpenTX.
Like many have heard on the field :-)

To put together a sound pack quickly and easily, there is a program called "TTS Automate"

Website: https://www.ttsautomate.com

This program converts a piece of text to audio and saves it in a specified folder and name.

The spoken language can also be selected.

It looks like this.

**Line number
**Folder** / Each line contains the path where audio file is stored.
I always maintain the structure of the SD card of OpenTX directly
**Filename** / the name of the audio file (note! From OpenTX v2.1.x a maximum of 6 characters are allowed, if larger they are ignored by OpenTX)
**Phrase to Speak** / Here the text that the audio file should receive. Occasionally you may have to play phonetically to get things properly spoken.
See inter alia lines 201 and 204 :-)
**Play** / Plays the file, and the file is created directly in the specified path

To the right of the screen:

**Open Phrase file** / here you can select the .PSV file
**Select Output Directory** / Where eventually the output including the specified path structure should be placed.
**Create new Phrase File** / Create a new project with this
**TTS Provider** / Select the Text To Speech Provider here. (To date, only Amazon Polly works correctly)
**Voice** / Select the voice here (I myself use Dutch Ruben, and I use Matthew for English)

![alt text](https://github.com/Hobby4life/OpenTX-Soundpacks-EN---NL/blob/main/TTS%20Automate/TTSAutomate.png)

Settings of TTS Automate so that they work well with OpenTX.

Most important here are the **Voice Options**

**Encode MP3 to WAV (checked)**
**Sample Rate: 32000Hz**
**Bits per sample: 16**

![alt text](https://github.com/Hobby4life/OpenTX-Soundpacks-EN---NL/blob/main/TTS%20Automate/TTSAutomateSettings.png)


**AUDACITY**
----------------------------


![alt text](https://github.com/Hobby4life/OpenTX-Soundpacks-EN---NL/blob/main/Audacity/Audacity 1 - Copy plugin to folder.png)

![alt text](https://github.com/Hobby4life/OpenTX-Soundpacks-EN---NL/blob/main/Audacity/Audacity 2 - Add plugin.png)

![alt text](https://github.com/Hobby4life/OpenTX-Soundpacks-EN---NL/blob/main/Audacity/Audacity 3 - Enable plugin.png)

![alt text](https://github.com/Hobby4life/OpenTX-Soundpacks-EN---NL/blob/main/Audacity/Audacity 4 - Batch chain setup.png)

![alt text](https://github.com/Hobby4life/OpenTX-Soundpacks-EN---NL/blob/main/Audacity/Audacity 5 - Batch chain apply.png)



