# YouTube Transcript Summarizer

## Project Description
This project is a Chrome extension that allows users to summarize the transcript of a YouTube video. It provides a convenient way to extract key points from lengthy transcripts, helping users quickly grasp the main ideas of a video.

## Features
- **Transcript Summarization**: Summarizes YouTube video transcripts based on a specified length.
- **Customizable Summary Length**: Allows users to set a maximum summary length for flexible results.
- **User-Friendly Interface**: Easy-to-use popup with a button to generate summaries directly.


## Screenshots<img width="1330" alt="Screenshot 2024-10-31 at 1 31 19 PM" src="https://github.com/user-attachments/assets/4ddaf0e5-0978-4809-9592-3208f2361082">
<img width="1330" alt="Screenshot 2024-10-31 at 1 31 31 PM" src="https://github.com/user-attachments/assets/e3b7f4a4-f6b5-431f-9308-64340854b713">
<img width="1273" alt="Screenshot 2024-10-31 at 1 33 39 PM" src="https://github.com/user-attachments/assets/9f9881d8-8c8a-4bb7-ae43-56546979ea03">

## Usage
1. Open a YouTube video and click on the **YouTube Transcript Summarizer** icon in the toolbar.
2. Adjust the **Max Length** input if you’d like to set a custom summary length.
3. Click **Summarize** to generate a summarized version of the transcript.
4. The summary will appear below the button.

## Project Structure
- `TranscriptApp.py`: Main script for fetching and summarizing transcripts.
- `Popup.html`: HTML for the Chrome extension’s popup window.
- `Popup.js`: JavaScript for handling user interactions in the popup.

## Requirements
- Python (for the summarization script)
- Chrome browser

## Future Improvements
- Adding language support for non-English transcripts.
- Enhancing summarization accuracy using advanced NLP techniques.
- Implementing a summary download feature.
