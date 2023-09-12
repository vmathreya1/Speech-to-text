# Speech to Text with ChatGPT 🔊

This Python application combines speech recognition with the power of ChatGPT by OpenAI to convert spoken language into text and generate text-based responses. It provides an interactive and user-friendly interface using Streamlit.


## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

Speech to Text with ChatGPT is a project that allows users to:

- Perform real-time speech recognition using a microphone.
- Utilize the recognized text as a prompt for the OpenAI GPT-3 model.
- Receive text-based responses generated by the model.

This project is built with Python, Streamlit, the SpeechRecognition library, and the OpenAI GPT-3 API. It offers a seamless way to interact with the ChatGPT model through voice input.


## Getting Started

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/speech-to-text-chatgpt.git

2. Navigate to the project directory

3. Install the required libraries : pip install -r requirements.txt

4. Set your OpenAI API key: Open speech_to_text.py and replace 'YOUR_OPENAI_API_KEY' with your actual OpenAI API key.

5. Run the Streamlit app

## Usage

- Click the "Voice Search" button to start recording.

- Speak into your microphone; the app will recognize your speech.

- The recognized text will be displayed as a prompt.

- ChatGPT will generate a text-based response based on your input.

- Experiment with different prompts and interactions

## Dependencies

This project relies on the following libraries and services:

- Streamlit: For creating the user-friendly web interface.
- SpeechRecognition: For audio capture and speech-to-text conversion.
- OpenAI GPT-3: For generating text-based responses.

Ensure that you have these dependencies installed before running the project.

## License
This project is licensed under the MIT License - see the LICENSE file for details.



