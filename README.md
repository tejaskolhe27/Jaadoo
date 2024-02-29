
---

# Jaadoo (Powered AI Desktop Assistant)

Jadoo is a Python-based desktop assistant that utilizes speech recognition and OpenAI's API to perform various tasks and engage in conversations with the user.

## Features

- **Voice Interaction**: Jadoo can understand voice commands and respond accordingly using speech synthesis.
- **Web Browsing**: Open specific websites such as YouTube, Wikipedia, and Google.
- **Music Playback**: Open and play music files on your system.
- **Time Information**: Get the current time from the system clock.
- **Launch Applications**: Open specified applications like FaceTime and Passky.
- **Artificial Intelligence Interaction**: Engage in conversations with Jadoo powered by OpenAI's text-generation model.

## Prerequisites

Before running Jadoo, ensure you have the following dependencies installed:

- Python 3.x
- Required Python packages (listed in `requirements.txt`)
- An API key for OpenAI's API stored in `config.py`

## Setup

1. Clone this repository to your local machine.
2. Install the required Python dependencies using `pip install -r requirements.txt`.
3. Obtain an API key for OpenAI's API.
4. Create a file named `config.py` in the project directory.
5. Inside `config.py`, define a variable named `apikey` and assign your OpenAI API key to it.

   ```python
   apikey = "****"
   ```

## Usage

1. Run the `main.py` script.
2. Speak commands or questions to Jadoo after it prompts "Listening...".
3. Jadoo will respond to your commands or questions accordingly.
4. Use specific commands like "Open YouTube", "What's the time?", "Using artificial intelligence", etc., to interact with Jadoo.

## Additional Notes

- Make sure your system has a working microphone for voice interaction.
- Jadoo's functionalities can be extended by modifying the `main.py` script according to your requirements.
- For any issues or feature requests, please open an issue on the GitHub repository.

---

