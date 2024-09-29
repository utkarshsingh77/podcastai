---
title: Open NotebookLM
emoji: 🎙️
colorFrom: purple
colorTo: red
sdk: gradio
sdk_version: 4.44.0
app_file: app.py
pinned: false
---

# Open NotebookLM

## Overview

This project is inspired by the NotebookLM tool, and implements it with open-source LLMs and text-to-speech models. This tool processes the content of a PDF, generates a natural dialogue suitable for an audio podcast, and outputs it as an MP3 file.

## Features

- **Convert PDF to Podcast:** Upload a PDF and convert its content into a podcast dialogue.
- **Engaging Dialogue:** The generated dialogue is designed to be informative and entertaining.
- **User-friendly Interface:** Simple interface using Gradio for easy interaction.

## Installation

To set up the project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/utkarshsingh77/podcastai.git
   cd pdf-to-podcast
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Set up API Key(s):**
   For this project, I am using LLama 3.1 405B hosted on Fireworks API as its JSON Mode supports passing a pydantic object. So, please set the API key as the `FIREWORKS_API_KEY` environment variable

2. **Run the application:**
   ```bash
   python app.py
   ```
   This will launch a Gradio interface in your web browser.

3. **Upload a PDF:**
   Upload the PDF document you want to convert into a podcast.

4. **Generate Audio:**
   Click the button to start the conversion process. The output will be an MP3 file containing the podcast dialogue.

## Acknowledgements

This project is forked from [`knowsuchagency/pdf-to-podcast`](https://github.com/knowsuchagency/pdf-to-podcast)

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for more information.
