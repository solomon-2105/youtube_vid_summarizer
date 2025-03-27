# YouTube Video Q&A System using LLMs

## Overview
This project is a **YouTube Video Question-Answering System** that extracts transcripts from YouTube videos and uses **Google Gemini API** to answer user queries based on the video's content.

## Features
- Extracts video transcripts using **YouTube Transcript API**.
- Processes the transcript and sends it to **Google Gemini API**.
- Answers user questions based on the video content.
- Provides an interactive way to analyze YouTube videos without watching them fully.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/solomon-2105/youtube_vid_summarizer
   cd youtube_vid_summarizer
   ```

## Usage
1. **Run the Jupyter Notebook** in VS Code or JupyterLab.
2. **Provide the YouTube video URL** in the designated cell and also create an api key using google ai studio.
3. The script will **fetch the transcript** automatically.
4. You can then **ask questions about the video**, and the **Gemini API** will generate relevant answers.

## Dependencies
- Python 3.8+
- `google-generativeai` (for Gemini API)
- `youtube-transcript-api` (for fetching video transcripts)
- `IPython`, `requests`, and other utility libraries

## API Configuration
1. Get an API key for **Google Gemini API**.
2. Add your API key in the script where required.
3. Ensure you have internet access while running the notebook.

## Example Workflow
1. **Input a YouTube video URL.**
2. **Transcript is extracted automatically.**
3. **Ask questions about the video content.**
4. **Receive AI-generated responses.**

## Future Enhancements
- Add a **GUI interface** for user-friendly interaction.
- Implement **multi-video summarization**.
- Store transcripts and responses in a **database for later reference**.

## Author
- **Solomon**
