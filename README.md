# Pocket_therapist

**Disclaimer:** Not all that is presented below is available or implemented in the actual project at the moment. Project Day 1 is 1/27/2025

## Overview

AI Therapy Companion is an unofficial AI-powered therapist chatbot designed to provide a supportive listening ear and basic mental health guidance. This project aims to create a personalized, ethical, and privacy-focused chatbot that can be used as a supplementary tool for mental well-being.

**Disclaimer:** This AI is not a replacement for professional mental health services. If you're experiencing a crisis or need immediate help, please contact a qualified mental health professional or emergency services.

## Features

- Deepseek R1 pre-trained model as the foundation
- Fine-tuned on therapy-related datasets
- Conversation saving and retrieval
- User-specific personalization mechanism
- Terminal-based interface
- Ethical safeguards and crisis detection

## Installation

(Add installation instructions here)

## Usage

(Add usage instructions here)

## Project Structure

- `main.py`: Entry point for the chatbot
- `model/`: Contains the Deepseek R1 model and fine-tuning scripts
- `data/`: Datasets used for fine-tuning
- `database/`: SQL scripts and database management
- `utils/`: Helper functions and utilities

## Datasets

The model is fine-tuned on the following datasets:
1. Transcripts of therapy sessions (anonymized and with consent)
2. Mental health resources and literature
3. Self-help books and articles

## Personalization Mechanism

The chatbot implements a personalization mechanism that allows it to learn from individual user interactions, creating a more tailored experience over time.

## Data Storage

User conversations and personalization data are stored using SQL, ensuring efficient retrieval and secure storage.

## Ethical Safeguards

- Clear disclaimers about the limitations of AI in mental health support
- Crisis detection algorithms with appropriate responses
- Privacy protections for user data

## Future Development

- Web application interface
- Enhanced personalization features
- Integration with professional mental health resources

## Key Considerations

1. **Privacy**: All user data is securely stored and encrypted.
2. **Ethical Use**: The chatbot is transparent about its capabilities and limitations.
3. **Continuous Learning**: The system is designed to improve over time based on interactions.
4. **Scalability**: The architecture supports efficient handling of multiple users.

