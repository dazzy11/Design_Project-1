# Personal Voice Assistant

This project is a Python-based voice assistant that uses speech recognition and text-to-speech capabilities to assist users with various tasks. The assistant can perform online searches, control basic applications, fetch weather reports, tell jokes, share advice, and much more.

## Features

### System Operations
- Open commonly used applications like Notepad, Discord, Camera, Calculator, and Command Prompt.

### Online Capabilities
- Fetch IP address.
- Search Wikipedia and read results aloud.
- Play videos on YouTube.
- Search queries on Google.
- Send WhatsApp messages.
- Send emails.
- Get the latest news headlines.
- Fetch weather reports for your city.

### Entertainment and Advice
- Tell random jokes.
- Provide random advice.
- Share trending movies.

## Technologies Used
- **Python**: Core programming language.
- **SpeechRecognition**: For recognizing user input.
- **pyttsx3**: For text-to-speech conversion.
- **Requests**: For fetching data from APIs (e.g., weather, IP lookup).
- **Decouple**: For managing environment variables.

## Prerequisites
1. Python 3.6 or above installed on your system.
2. Required Python modules:
   - `speechrecognition`
   - `pyttsx3`
   - `requests`
   - `decouple`
3. Microphone for voice input.
4. Internet connection for online functionalities.

## Setup Instructions
1. Clone or download the repository.
2. Install the required Python modules using:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up a `.env` file in the project root with the following keys:
   ```
   USER=YourName
   BOTNAME=AssistantName
   ```
4. Run the script:
   ```bash
   python script_name.py
   ```

## Usage
1. Start the assistant and wait for the greeting.
2. Speak commands such as:
   - "Open Notepad"
   - "What is my IP address?"
   - "Search Wikipedia for Python programming."
   - "Play [video name] on YouTube."
   - "Tell me a joke."
3. The assistant will execute the commands and provide responses through voice and text.

## Customization
- Modify `functions.online_ops` and `functions.os_ops` to add or change functionality.
- Update the `opening_text` list in `utils.py` for customized greetings.

## Notes
- Ensure your microphone and speakers are working correctly.
- Adjust the speech recognition threshold (`r.pause_threshold`) as needed.
- Some features depend on external APIs; ensure API access is functional.

## License
This project is licensed under the MIT License. Feel free to use and modify it for personal or educational purposes.

## Acknowledgements
- Inspired by personal voice assistant systems like Alexa and Google Assistant.
- Special thanks to the developers of Python libraries used in this project.

