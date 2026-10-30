# Scam Message Investigator

### AI-Powered Scam Detection Using Local Large Language Models

## Project Overview

Scam Message Investigator is an AI-powered application designed to analyze suspicious SMS messages, emails, WhatsApp messages, and online notifications.

The application uses the Gemma 3 (1B) Large Language Model through Ollama to identify potential scam indicators, classify risk levels, explain warning signs, and provide safety recommendations.

The application runs locally, allowing users to analyze messages without sending them to an external AI API.

## Objectives

* Identify potentially fraudulent messages.
* Detect suspicious words and misleading content.
* Classify messages based on risk levels.
* Generate AI-powered investigation reports.
* Provide recommendations to avoid online scams.
* Improve awareness of digital fraud and cybersecurity.

## Features

* **AI-Based Message Analysis:** Analyzes suspicious messages using Gemma 3 (1B).
* **Risk Classification:** Categorizes messages into Low, Medium, and High Concern.
* **Risk Score:** Generates an AI-estimated risk score from 0 to 100.
* **Warning Sign Detection:** Identifies suspicious links, OTP requests, urgent language, fake job offers, and financial fraud indicators.
* **Investigation Summary:** Provides explanations of suspicious message characteristics.
* **Safety Recommendations:** Suggests actions to protect users from potential scams.
* **Report Download:** Allows users to download investigation reports in JSON format.
* **Local AI Processing:** Uses Ollama to run the AI model locally.

## Technologies Used

| Technology   | Purpose                         |
| ------------ | ------------------------------- |
| Python       | Application development         |
| Streamlit    | Web application interface       |
| Ollama       | Local LLM execution             |
| Gemma 3 (1B) | AI message investigation        |
| Requests     | Communication with Ollama API   |
| JSON         | Investigation report generation |

## Application Modules

### 1. Message Input Module

Accepts suspicious messages from users for investigation.

### 2. AI Investigation Module

Processes the submitted message using the Gemma 3 (1B) model.

### 3. Risk Classification Module

Assigns an estimated risk level based on the AI analysis.

### 4. Warning Sign Detection Module

Identifies suspicious phrases and explains their potential risks.

### 5. Safety Recommendation Module

Provides security suggestions to help users avoid potential scams.

### 6. Report Generation Module

Generates downloadable JSON investigation reports.

## Advantages

* Easy-to-use interface.
* Local AI processing.
* No external AI API key required.
* Fast message investigation for short inputs.
* Helps improve cybersecurity awareness.
* Provides understandable investigation results.

## Limitations

* AI-generated results may not always be accurate.
* A suspicious message cannot be conclusively verified using text analysis alone.
* Internet access may be required to download the model initially.
* The application requires Ollama to be running locally.
* Risk scores are estimates, not statistically validated fraud probabilities.

## Future Enhancements

* SMS and email integration.
* URL reputation checking.
* Multilingual scam message detection.
* Image-based scam detection using OCR.
* Real-time scam alerts.
* Database integration for investigation history.
* PDF report generation.

## Security Disclaimer

This application is developed for educational and cybersecurity awareness purposes.

AI-generated classifications should not be treated as definitive proof of fraud or authenticity. Users should verify suspicious communications through official organizations and never share OTPs, passwords, PINs, or banking credentials.

