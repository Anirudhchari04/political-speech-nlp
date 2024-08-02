# political-speech-nlp
# Transcribing and Analyzing Audio Files with Wav2Vec2

This repository contains a series of notebooks that explore the transcription of various audio files using the Wav2Vec2 model from Hugging Face. The project demonstrates the model's capabilities on different types of audio content, including short clips, poetry recitals, political speeches, and other spoken content.


## Project Overview

This project utilizes the Wav2Vec2 model for automatic speech recognition (ASR) to transcribe audio files into text. The notebooks cover a range of audio lengths and styles, from short 62-second clips to longer speeches and poetry recitals. The transcriptions aim to accurately capture the spoken content, including diverse accents and delivery formats.

## Notebooks

### 1.0_wav2vec2_short.ipynb
- Focuses on transcribing a short audio clip (62 seconds) using Wav2Vec2. The notebook evaluates the model's performance on different accents and discusses the challenges of handling longer audio clips.

### 2.0_wav2vec2_poetry.ipynb
- Applies Wav2Vec2 to transcribe a poetry recital, specifically Amanda Gorman's poem from the 2021 U.S. Presidential Inauguration. The notebook addresses issues related to processing longer audio files and splitting them for efficient transcription.

### 2.1_wav2vec2_poetry_alt.ipynb
- An alternative approach to transcribing poetry using the Wav2Vec2 model. This notebook may include different preprocessing steps or evaluation metrics.

### 3.0_transcribe_translate_sentiment_analysis.ipynb
- This notebook extends the transcription capabilities by translating the transcribed text into another language and performing sentiment analysis on the translated text. It explores the integration of translation models and sentiment analysis tools with the Wav2Vec2 model.

### 3.1_transcribe_summarise.ipynb
- Focuses on transcribing and summarizing longer audio content. The notebook demonstrates how to use the Wav2Vec2 model for transcription and then applies summarization techniques to condense the transcribed text into a more concise format.

## Features

- **Transcription**: Converts spoken language into text using the Wav2Vec2 model.
- **Handling Long Audio**: Implements methods for splitting long audio files to avoid memory issues.
- **Translation**: Translates transcriptions into different languages.
- **Sentiment Analysis**: Analyzes the sentiment of the translated text.
- **Summarization**: Condenses transcribed text into concise summaries.
- **Error Handling**: Discusses common errors and inaccuracies in ASR outputs.

## Installation

To set up the environment and run the notebooks, follow these steps:

```bash
git clone https://github.com/yourusername/transcribing-audio-wav2vec2.git
cd transcribing-audio-wav2vec2
pip install -r requirements.txt
