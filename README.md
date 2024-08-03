# TeamSpeak 3 Bot with Audio Transcription

Welcome to the TeamSpeak 3 Bot with Audio Transcription project! This bot connects to a TeamSpeak 3 server, listens to audio streams, and transcribes them into text using advanced speech recognition technologies.

## Features

- Connects to a TeamSpeak 3 server.
- Listens to and records audio from TeamSpeak channels.
- Transcribes audio to text using state-of-the-art speech-to-text APIs.
- Logs transcriptions and errors for review.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or higher
- A TeamSpeak 3 server with appropriate permissions for the bot
- API keys for speech-to-text services (e.g., Google Cloud Speech-to-Text, Microsoft Azure Speech, etc.)
- Basic understanding of how TeamSpeak 3 bots work

## Installation
1. Clone the repository
2. Create a Virtual environment:

3. Install the required Python packages
   install pyaudio
   install ts3
   install numpy
   
4. Configure the bot
   {
  "teamspeak": {
    "host": "your.teamspeak.server",
    "port": 9987,
    "username": "bot_username",
    "password": "bot_password"
  },
  "speech_to_text": {
    "api_key": "your_speech_to_text_api_key",
    "service": "google"  // or "azure"
  }
}

Usage
1. Run the bot
2. Monitor the bot's output
   The bot will connect to the TeamSpeak server and start listening to audio channels. Transcriptions and any errors will be logged in the logs directory

Configuration
The bot can be customized through the config.json file. Here’s a brief overview of the configuration options:

teamspeak.host: The address of your TeamSpeak 3 server.
teamspeak.port: The port your TeamSpeak server is running on (default is 9987).
teamspeak.username: The username for the bot to connect with.
teamspeak.password: The password for the bot.
speech_to_text.api_key: Your API key for the chosen speech-to-text service.
speech_to_text.service: The speech-to-text service you are using (google or azure).

Troubleshooting
Bot fails to connect to TeamSpeak server: Check your server address, port, and bot credentials.
Transcriptions are not being generated: Verify your API key and ensure you have set the correct speech-to-text service in the configuration.

Contributing
Feel free to contribute to this project! Open issues and pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Contact
If you have any questions or suggestions, please contact your leetunya41@gmail.com
