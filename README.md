# Telegram LLM Chatbot

A simple Telegram chatbot connecting to a locally running Ollama instance.

## Run the Ollama locally

Install and run a model by using the following commands:

```
curl -fsSL https://ollama.com/install.sh | sh
ollama run granite-code:3b
```

## Register the Telegram bot

Chat with Botfather and create a new token, like described in the manual.

https://core.telegram.org/bots

Update the Telegram token in the source code.

## Install Python libraries

You need Python 3.x to run the application and `pip` to install the dependencies.

```
pip install ollama
pip install python-telegram-bot --upgrade
```

## Run the application

I mean, just run it. :)
