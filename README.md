# walk-safe-talk-safe
AI safety helpline for when you're walking in a shady neighborhood and need a fake conversation to deter suspicious characters.

To test this app call +1 (866) 606-9834.

---

### Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [TODO](#todo)
4. [Installation](#installation)
5. [Usage](#usage)

---

## Introduction
i'm like a tiny 5'1" girl and you know, sometimes i just happen to be in a shady area. and it's nice to call someone to talk you through it to make sure you're getting to your destination. sometimes you don't even have anything to talk about. but you gotta make sure someone is there for you. but if nobody is there for you, AI can pretend to be there for you and deter any shady characters from acting on anything.

## Features
* Call the AI for a fake conversation on the phone, where the AI is concerned about your safety.

## Todo
* Ask the AI to text a friend for you about your progress and where you are.
* If you start the call on a gendered name, the voice will change to the appropriate gendered voice.

## Installation
### Requirements
* A [Twilio](https://twilio.com/) account
* An [ngrok](ngrok.com) account
* An [OpenAI](https://platform.openai.com/) account
* An [ElevenLabs](https://elevenlabs.io/) account

### Installation steps
1. Clone the repository:
   ```bash
   git clone https://github.com/bella-le/walk-safe-talk-safe.git
   ```
2. Install dependencies:
    * Download Vosk model here: https://alphacephei.com/vosk/models
    * `pip3 install -r requirements.txt`
3. Setup your `.env` file and include relevant API keys:
    ```bash
    # https://console.twilio.com
    TWILIO_ACCOUNT_SID=
    TWILIO_AUTH_TOKEN=

    # https://dashboard.ngrok.com/get-started/your-authtoken
    NGROK_AUTH_TOKEN=

    # https://platform.openai.com/account/api-keys
    OPENAI_API_KEY=

    # https://elevenlabs.io
    ELEVENLABS_API_KEY=
    ```

## Usage
1. Run the script at `python3 ai_phone_call.py` 
2. Call your robot’s number