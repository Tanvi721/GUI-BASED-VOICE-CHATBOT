# GUI and Voice Based Chatbot 🤖🎤


📌 Project Overview

This project is a chatbot application that supports both Graphical User Interface (GUI) interaction and Voice-based interaction.
It is built using Python with libraries like Tkinter, SpeechRecognition, and pyttsx3, and demonstrates how Natural Language Processing (NLP) can be integrated with interactive applications.

🚀 Features

🖥️ GUI-based chat interface using Tkinter.

🎙️ Voice input support with SpeechRecognition.

🔊 Text-to-Speech (TTS) responses with pyttsx3.

📂 Pre-trained chatbot model using intents and responses.

🔄 Handles both text and voice conversations seamlessly.

🛠️ Technologies Used

Python 3.x

Tkinter – GUI framework

SpeechRecognition – Voice input

pyttsx3 – Text-to-speech conversion

NLTK / TensorFlow – Natural Language Processing (if used in your model)

📂 Project Structure
├── chatbot_model.h5       # Trained chatbot model
├── classes.pkl            # Saved class labels
├── words.pkl              # Saved tokenized words
├── intents.json           # Dataset of intents and responses
├── GUI based and Voice based chatbot.ipynb   # Main notebook
└── README.md              # Project documentation

⚡ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Install required dependencies:

pip install -r requirements.txt


Example dependencies:

tkinter
speechrecognition
pyttsx3
nltk
tensorflow


Run the notebook or script:

jupyter notebook "GUI based and Voice based chatbot.ipynb"


or if you convert to .py:

python chatbot.py

🎯 How It Works

User can type or speak queries.

Chatbot processes the input using trained intents.

Response is displayed in the GUI and optionally spoken using TTS.

📸 Screenshots (Optional)

Add screenshots of your chatbot GUI here for better presentation.

🔮 Future Enhancements

🌐 Add support for multilingual conversations.

💬 Integrate with external APIs (e.g., weather, news).

🤖 Deploy chatbot as a web application (Flask/Django + React).

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repo and submit PRs.

📜 License

This project is licensed under the MIT License – you’re free to use, modify, and distribute it.
