# Scam Message Investigator

## Project Overview
Scam Message Investigator is an AI-powered application that analyzes suspicious messages and identifies potential scam indicators using a locally running Large Language Model (LLM). It uses Ollama and the Gemma 3 (1B) model to generate an investigation report.

## Objectives
- Analyze suspicious messages using AI.
- Identify potential scam warning signs.
- Classify messages by risk level.
- Provide practical safety recommendations.
- Help users recognize common online scams.

## Technologies Used
- Python
- Streamlit
- Ollama
- Gemma 3 (1B)
- Requests
- JSON

## Features
- Simple and user-friendly interface.
- AI-powered message analysis.
- Risk classification: Low Concern, Medium Concern, and High Concern.
- Identification of suspicious phrases.
- Explanation of potential warning signs.
- Recommended safety actions.
- Investigation limitations.

## Project Structure
```text
ScamMessageInvestigator/
└── app.py
```

## Installation and Setup

### 1. Install Python
Download Python from:
https://www.python.org/downloads/

### 2. Install Ollama
Download Ollama from:
https://ollama.com/

### 3. Download the AI Model
Open Command Prompt and run:

```bash
ollama pull gemma3:1b
```

### 4. Install Required Libraries
Open the terminal in VS Code and run:

```bash
pip install streamlit requests
```

### 5. Run the Application
Navigate to your project folder and execute:

```bash
streamlit run app.py
```

The application will open in your web browser.

## How It Works
1. The user enters a suspicious message.
2. The application sends the message to the local Ollama API.
3. The Gemma 3 model analyzes the message.
4. The model generates a structured JSON report.
5. Streamlit displays the risk level, summary, warning signs, recommended actions, and limitations.



## Advantages
- Uses a locally running AI model.
- Does not require a paid cloud AI API.
- Provides explanations for potential warning signs.
- Offers practical digital safety recommendations.
- Has a simple and accessible interface.

## Limitations
- AI-generated assessments may not always be accurate.
- The application cannot independently verify a sender's identity.
- A message may not provide enough information to confirm whether it is genuine.
- A low-risk assessment does not guarantee that a message is safe.
- Ollama and the required model must be installed and running locally.

## Future Enhancements
- Screenshot-based message analysis.
- Suspicious URL analysis.
- Downloadable investigation reports.
- Message history.
- Support for multiple languages.

## Conclusion
Scam Message Investigator demonstrates how local Large Language Models can help users identify potential scam indicators in suspicious messages. It provides a risk assessment, explanations, and safety recommendations to support informed decisions.

