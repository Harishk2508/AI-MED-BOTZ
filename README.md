# AI-MED-BOTZ
# Doctor Med - AI Medical Assistant

Doctor Med is an AI-powered medical assistant developed by Med Botz. It utilizes OpenAI's GPT-3.5 model to provide medical advice and prescriptions based on user input.

## Features:
- Listens to user's voice input using speech recognition.
- Processes user's input and generates a response using OpenAI's GPT-3.5 model.
- Provides medical advice and prescriptions.
- Terminates the conversation upon user's request.

## Dependencies:
- OpenAI Python API
- SpeechRecognition
- pyttsx3

## Usage:
1. Install the required dependencies using `pip install openai speechrecognition pyttsx3`.
2. Run the script `doctor_med.py`.
3. Speak to the AI assistant and ask medical queries.
4. End the conversation by saying "Thank you doctor".

## Limitations:
- Relies on internet connection for accessing the OpenAI API.
- Accuracy of responses may vary depending on the input and the capabilities of the GPT-3.5 model.
