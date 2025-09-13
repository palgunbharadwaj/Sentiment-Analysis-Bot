# Sentiment Analysis Bot

A simple web application that performs sentiment analysis on text input using Hugging Face's Transformers library and Gradio for the user interface.

## Features
- Real-time sentiment analysis of text input
- Simple and intuitive web interface
- Built with Python, Gradio, and Hugging Face Transformers
- Fast and lightweight

## Demo

![Sentiment Analysis Demo](https://raw.githubusercontent.com/palgunbharadwaj/Sentiment-Analysis-Bot/main/image-1.webp)
*Screenshot of the Sentiment Analysis Bot in action*

## Getting Started

### Prerequisites
- Python 3.6 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-bot.git
   cd sentiment-analysis-bot
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   .\venv\Scripts\activate  # On Windows
   source venv/bin/activate  # On macOS/Linux
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Run the application:
   ```bash
   python app.py
   ```

2. Open your web browser and navigate to the URL shown in the terminal (usually http://localhost:7860)

3. Enter a sentence in the text box and see the sentiment analysis results!

## How It Works

The application uses a pre-trained sentiment analysis model from Hugging Face's Transformers library to analyze the sentiment of the input text. The model classifies the text as either POSITIVE or NEGATIVE and provides a confidence score.

## Dependencies

- gradio
- transformers
- torch

Created with ❤️ using Python, Gradio, and Hugging Face Transformers