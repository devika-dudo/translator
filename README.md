# translator

Team Name: Cybersirens

Team Members
-Member1 : Fathima Parveen
-Member2 : Devika S Kumar

Project Overview

Our goal is to develop an offline multilingual translator that can translate speech from one language to another without requiring an internet connection. As of now, we have implemented Arabic-to-English translation.

🛠️ How It Work

Speech Input: The microphone records Arabic speech.

Speech-to-Text Conversion: Using the Vosk model, the Arabic speech is transcribed into text.

Text Translation: The transcribed Arabic text is translated to English using Argos Translate.

Text-to-Speech Output: The translated English text is converted into speech using pyttsx3.

📌 Features

✅ Works offline
✅ Supports Arabic-to-English translation (more languages to be added)
✅ Real-time speech recognition and translation
✅ Converts translated text to speech output

📦 Dependencies

To run this project, install the following Python libraries:

pip install vosk argostranslate pyttsx3 sounddevice

🚀 How to Run

Clone the repository:

git clone https://github.com/your-repo/offline-translator.git
cd offline-translator

Run the script:

python main.py

📌 Future Enhancements

🔹 Add support for more languages
🔹 Improve translation accuracy
🔹 Enhance UI for a better user experience

📜 Diagram

