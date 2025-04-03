# Alfred - Your Voice Assistant

Alfred is a voice assistant application that helps you perform various tasks using voice commands. It utilizes Python libraries such as `pyttsx3` for text-to-speech, `speech_recognition` for recognizing voice commands, and `wikipedia` for fetching information.

## Features

- Greet the user based on the time of day.
- Take voice commands and perform actions such as:
  - Search Wikipedia.
  - Open websites (YouTube, Google, Stack Overflow).
  - Tell the current time.
  - Send emails.

## Installation

To run this project, you need to have Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

### Required Libraries

Install the required libraries using pip:

```bash
pip install pyttsx3 speechrecognition wikipedia webbrowser
```

## Usage

1. Clone the repository or download the `main.py` file.
2. Open a terminal and navigate to the directory containing `main.py`.
3. Run the application:

```bash
python main.py
```

4. Follow the voice prompts and give commands such as:
   - "Open YouTube"
   - "Tell me the time"
   - "Search Wikipedia for Python programming"

## Note

Make sure to replace the email credentials in the `sendEmail` function with your own email and password to enable email functionality.

## License

This project is open-source and available under the MIT License created by Khushman Singh Kalsi (kskalsi0108@gmail.com) .
