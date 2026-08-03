# Streaming Chat Demo

A simple Python example demonstrating how to use the **Groq Python SDK** to interact with Large Language Models (LLMs) using **streaming responses**.

This project sends a prompt to a Groq-hosted model and prints the generated response in real time.

---

## Features

- Uses the official Groq Python SDK
- Loads API key securely using `.env`
- Supports streaming chat completions
- Easy to understand and modify
- Minimal example for beginners

---

## Tech Stack

- Python 3.x
- Groq Python SDK
- python-dotenv

---

## Code Overview

The application performs the following steps:

1. Loads the API key from the `.env` file.
2. Creates a Groq client.
3. Builds a chat message.
4. Sends the request to the selected model.
5. Streams the response.
6. Prints each generated token immediately.

---

