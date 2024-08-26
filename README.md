# AI-Powered Voice-Enabled Medical Query Platform

## Overview
This project is an AI-powered platform designed to help doctors query patient data using voice input. The platform integrates MongoDB for storing medical records and OpenAI's API for natural language processing. Additionally, it supports voice-to-text input and provides text-to-speech responses, allowing for seamless, hands-free interaction.

## Features
- **Voice-to-Text Input:** Converts doctor’s voice input into text for querying the medical data.
- **Natural Language Querying:** Uses OpenAI's API to process and understand queries about patient data.
- **Text-to-Speech Response:** Generates spoken responses, making the interaction feel conversational.
- **MongoDB Integration:** Stores and retrieves patient data efficiently.
  

## Technologies Used
- **Python**
- **MongoDB**
- **OpenAI API**
- **SpeechRecognition Library** (for voice input)
- **pyttsx3 Library** (for text-to-speech output)
- **Jupyter Notebook** (for development and demonstration)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shreya-847/voice-enabled-medical-query-platform.git
   cd voice-enabled-medical-query-platform

2. Install required dependencies:
   pip install -r requirements.txt
3. Set up your MongoDB database and insert medical data (Set your MongoDB Key)
4. Set up your OpenAI API key: export OPENAI_API_KEY='your_openai_api_key'

**Example Interaction:**

```bash
Enter a question to ask about the medical data (or type 'exit' to finish): How many patients are there?
Response: There are two patients.

Enter a question to ask about the medical data (or type 'exit' to finish): What are their names?
Response: The names of the patients are John Doe and Jane Smith.

Enter a question to ask about the medical data (or type 'exit' to finish): Give a brief of the condition of Jane Smith.
Response: Jane Smith is a 25-year-old female with a hemoglobin level of 13 and normal iron levels. She had her last dental visit on May 10th with no reported issues. Her medical history includes asthma, and she takes albuterol for medication. Overall, Jane Smith appears to be in good health with no significant ongoing medical concerns.

Enter a question to ask about the medical data (or type 'exit' to finish): exit



