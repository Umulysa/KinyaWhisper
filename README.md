🗣️ Kinyarwanda Voice Assistant

A simple yet powerful voice assistant built with Python. It listens to your voice in Kinyarwanda, transcribes it using Google Speech Recognition, finds a matching response, and replies using speech via gTTS and pygame. It's your digital homie that understands the vibes 🇷🇼💬
📦 Features

    🎙️ Voice Recording
    Records audio from your microphone in real-time.

    🧠 Speech Recognition
    Converts your Kinyarwanda speech to text using Google Speech Recognition.

    🤖 Response Matching
    Finds a predefined answer to your question or gives a fallback message.

    🔊 Text-to-Speech
    Speaks back the answer using Google Text-to-Speech and plays it with pygame.

🛠️ Requirements

Make sure you have Python 3 installed. Then install the required packages:

pip install sounddevice soundfile SpeechRecognition gTTS pygame

Also, ensure you have portaudio and a microphone properly set up on your system.

For Linux (e.g., Ubuntu), you might need:

sudo apt install portaudio19-dev python3-pyaudio

🚀 How to Run

    Clone this repo or copy the code into a .py file.

    Run the script:

python your_file_name.py

    Speak your heart out (in Kinyarwanda, of course).

    Hear your assistant reply!

🧩 Example Questions You Can Ask
You Say (in Kinyarwanda)	Assistant Replies
amakuru yawe	Ni meza cyane, urakoze.
witwa nde	Nitwa Umufasha w'Ikoranabuhanga.
urimo gukora iki	Ndimo kugufasha!
uri nde	Ndi robot y'umunyarwanda.
wakora iki	Nshobora kukumva no kugusubiza.
🧠 Notes

    The assistant uses the Kinyarwanda locale (rw-RW) when transcribing.

    The gTTS library supports limited Kinyarwanda voice synthesis — so some accents might come out English-like.

    Extendable: Want more questions and answers? Just add to the qa_pairs dictionary!
