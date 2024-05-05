# GPT-4 Voice Chat Application

A Python-based application that integrates OpenAI's GPT-4 with voice recognition and synthesis to provide a voice assistant experience. The assistant can be triggered using a wakeup phrase and responds using natural language.

## Features
- **Voice Wakeup Phrase**: Customize the wakeup phrase to initiate the conversation.
- **Continuous Interaction**: Keeps the conversation flowing after activation.
- **Voice Configuration**: Configure text-to-speech and speech-to-text options.
- **Menu Bar Icon**: A handy menu bar application for easy access and customization.
  
## Requirements
- Python 3.7+
- OpenAI GPT-4 API key
- Additional Python libraries specified in `requirements.txt`

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/gpt4-voice-chat.git
   cd gpt4-voice-chat
   ```
2. **Create a Virtual Environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set Up Configuration:**
   - Add your OpenAI GPT-4 API key to `config/config.py`
   - Customize the settings in the `settings.json` file

## Usage

1. **Run the Application:**
   ```bash
   python main.py
   ```
2. **Interacting with the Application:**
   - Say your customized wakeup phrase to activate the assistant
   - Speak your question or command after hearing a beep
   - Listen to the response synthesized using the configured TTS system

## Customization

- **Wakeup Phrase:** Modify the wakeup phrase using the settings panel accessible via the menu bar icon.
- **Voice Options:** Adjust the text-to-speech and speech-to-text settings via the settings panel.
- **Integration:** The app can be extended with additional features using the modular architecture provided.

## Contributing
Feel free to contribute by submitting pull requests or opening issues. Make sure to follow the established coding guidelines and document your changes properly.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
```

You can customize this README further to reflect your specific project details.