# Audio to Summarized Transcript Project

## Overview

This project demonstrates a pipeline for converting audio files into text transcripts and then summarizing the text using advanced Hugging Face models. It integrates audio transcription and text summarization, featuring a user-friendly interface built with Gradio.

## Files

- **`pipeline_notebook.ipynb`**: Demonstrates the use of Hugging Face models for audio-to-text transcription and text summarization with code example and explanation.
- **`gradio_notebook.ipynb`**: Illustrates various Gradio components and their functionalities, showcasing how to build interactive web interfaces.
- **`full_implementation_notebook.ipynb`**: Combines audio transcription and text summarization with Gradio, providing a complete interactive application with code that integrates all components.
- **`results.csv`**: Contains output data from the full implementation notebook, including transcripts and summaries.
- **`video_demo.mp4`**: A walkthrough video of the full implementation notebook, demonstrating how to use the interactive features.

## Code Overview

- **`pipeline_notebook.ipynb`**: This notebook shows how to use the Whisper model for converting audio to text and the PEGASUS model for summarizing the text. It includes functions to process audio and summarize text, with example code snippets.

- **`gradio_notebook.ipynb`**: Features a demonstration of Gradio components such as `Textbox`, `Slider`, and `Audio`. The code examples illustrate how to build and customize Gradio interfaces for different types of user inputs and outputs.

- **`full_implementation_notebook.ipynb`**: Integrates the transcription and summarization functionality into a Gradio interface. The notebook contains code that allows users to upload audio files, adjust summary length settings, and view both the transcript and summary. It showcases how to combine multiple models and Gradio components into a cohesive application.

## Hugging Face Pipeline The Hugging Face text-to-text pipeline involves two main steps:

1. **Audio-to-Text Transcription**: Using models like Whisper to convert audio files into text.

 2. **Text Summarization**: Using models like PEGASUS to generate concise summaries of the transcribed text.


## Instructions

1. Open **`full_implementation_notebook.ipynb`** to run the complete pipeline.
2. Use the Gradio interface within the notebook to upload audio files and receive summarized transcripts.

## Expected Outputs from Gradio Interface

- **Uploaded Audio File**: Confirmation of the uploaded file.

- **Transcribed Text**: Display of the transcribed text from the audio file.

- **sliders**: Interactive controls for adjusting summary length.

- **Summarized Text**: Display of the summarized version of the transcribed text.

## Hugging Face Project

Explore the deployed Hugging Face project here: [https://huggingface.co/spaces/ShahadFawaz99/Audio_Transcription_and_Summarization]

## Video Walkthrough

Watch the video demonstration here: [Link to video demo]
