# translator
OFFLINGO : PORTABLE BILINGUAL TRANSLATOR THAT WORKS OFFLINE IN REMOTE AREAS

Team Name: Cybersirens

Team Members
-Member1 : Fathima Parveen
-Member2 : Devika S Kumar

Project Overview

Our goal is to develop an offline multilingual translator that can translate speech from one language to another without requiring an internet connection. As of now, we have implemented Arabic-to-English translation.

PROBLEM STATEMENT
Language barriers pose significant challenges in regions with limited internet access, affecting communication in critical sectors like healthcare, emergency response, and education. Existing translation solutions depend on cloud-based services, making them unreliable in offline environments.

To overcome this, we are developing an offline multilingual speech translator that enables seamless language translation without an internet connection. Our initial implementation focuses on Arabic-to-English translation, ensuring real-time, reliable communication in low-connectivity areas.


PROPOSED SOLUTION:

We have developed "OffLingo", an offline speech-to-speech translator that enables real-time language translation without internet access. Unlike cloud-based solutions, it processes translations locally using Argos Translate, ensuring privacy, security, and accessibility.  

Our initial implementation focuses on Arabic-to-English translation, with plans to expand to additional languages. We are also exploring Raspberry Pi integration to enhance portability and usability in low-connectivity environments.  

OffLingo is designed for a range of users, including travelers, humanitarian workers, emergency responders, and military personnel. Its offline capabilities make it an invaluable tool for military personnel in the field, enabling seamless communication in critical situations without the need for an internet connection. The system bridges language barriers in remote or conflict zones, enhancing coordination and operational efficiency.


 How It Work:

Speech Input: The microphone records Arabic speech.
Speech-to-Text Conversion: Using the Vosk model, the Arabic speech is transcribed into text.
Text Translation: The transcribed Arabic text is translated to English using Argos Translate.
Text-to-Speech Output: The translated English text is converted into speech using pyttsx3.

TECHNOLOGICAL COMPONENTS REQUIRED;

1.Raspberry pi 4
2.Audio Amplifier :PAM8403
3.Microphone
4.Switch-2 spst 
5.270 ohm resistors-2
6.150 ohm resistor-2
7.10 micro F capacitors-2
10.0.1 micro F capacitor-2
11.Speaker
12.wires
13.Micro SD card for pi


📌 Features

✅ Works offline
✅ Supports Arabic-to-English translation (more languages to be added)
✅ Real-time speech recognition and translation
✅ Converts translated text to speech output

Installations
pip install vosk sounddevice numpy
!apt-get install portaudio19-dev
!pip install sounddevice
!apt-get install -y portaudio19-dev
!pip install pyaudio
!pip install vosk
!pip install vosk soundfile
!pip install argostranslate
!pip install pyttsx3
!sudo apt-get install espeak-ng
!pip install pyttsx3 pydub
!apt-get install ffmpeg

Repo link:

https://github.com/devika-dudo/translator.git

circuit diagram:
![image](https://github.com/user-attachments/assets/d6657d0d-a7e0-4d16-818e-7544374aaddb)

SCREENSHOTS OF WORK:
![WhatsApp Image 2025-02-02 at 9 47 38 AM](https://github.com/user-attachments/assets/5271394e-cda2-4044-820c-ded773d53ec0)

![WhatsApp Image 2025-02-02 at 9 48 05 AM](https://github.com/user-attachments/assets/f0a8c2e2-be4b-4a15-82a8-1705d05d035c)

![image](https://github.com/user-attachments/assets/05b1f0e4-d865-47a3-b8e5-b13cf1a5b38b)

WORKING VIDEO:
