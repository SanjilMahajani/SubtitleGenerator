# Video Transcription and Subtitle Generator

This project provides an end-to-end solution for transcribing videos and generating subtitles dynamically using OpenAI's Whisper model. It automatically extracts audio from video files, transcribes and translates the audio, and generates a subtitle file (`.srt`) that can be used with the original video.

## Features

- **Automatic Audio Extraction**: Extracts audio from video files using `ffmpeg`.
- **Transcription**: Uses OpenAI's Whisper model for high-quality transcription and translation.
- **Dynamic Subtitle Generation**: Creates subtitles in `.srt` file format.
- **GPU Acceleration**: Supports GPU for faster transcription.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Acknowledgements](#acknowledgements)

## Installation

1. **Clone the Repository**

  Clone this repository or directly click on the google collab link provided in the "Video_subtitle_creator.ipynb"

2. **Usage**

  - Upload the video in the google collab directory and copy it's path and paste it in the function, similarly also mention where do you need to store your audio and subtitle files
  - Use the GPU(recommended) for faster results, which you can do it by going in runtime->Change runtime and selecting the t4 GPU
  - After that just click "Run all" to get your subtitle file in your preferred location

3. **Requirements**

  - Python 3.x
  - ffmpeg
  - Whisper
  - Torch (PyTorch)

4. **Acknowledgments**

  - OpenAI Whisper for the transcription model.
  - Google Colab for providing an accessible environment for running GPU-intensive tasks.
  - All contributors to the project.

