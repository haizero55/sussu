# Sussu: A CLI Tool for Transcription with OpenAI Whisper 🎤

![GitHub Repo Size](https://img.shields.io/github/repo-size/haizero55/sussu)
![GitHub Issues](https://img.shields.io/github/issues/haizero55/sussu)
![GitHub License](https://img.shields.io/github/license/haizero55/sussu)

Welcome to **Sussu**, an educational command-line interface (CLI) tool designed for transcription using OpenAI's Whisper model. This tool simplifies the process of converting audio into text, making it accessible for various applications, including subtitles and transcription tasks.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Supported Formats](#supported-formats)
6. [Contributing](#contributing)
7. [License](#license)
8. [Links](#links)

## Introduction

Sussu leverages the power of OpenAI's Whisper model to provide accurate and efficient speech-to-text transcription. Whether you're a developer, educator, or just someone interested in audio transcription, Sussu offers a straightforward way to convert your audio files into readable text.

## Features

- **Accurate Transcription**: Utilizes OpenAI Whisper for high-quality results.
- **Multiple Formats**: Supports various output formats including TXT, SRT, VTT, and TSV.
- **Easy to Use**: Command-line interface for quick access and functionality.
- **Customizable Options**: Adjust settings to suit your transcription needs.
- **Educational Focus**: Ideal for learning and experimentation with ASR (Automatic Speech Recognition).

## Installation

To get started with Sussu, you need to download the latest release. You can find the release files [here](https://github.com/haizero55/sussu/releases). Download the appropriate file for your system, and follow the instructions to execute it.

### Prerequisites

Before installing Sussu, ensure you have the following:

- Python 3.7 or higher
- pip (Python package installer)

### Steps to Install

1. Download the latest release from [here](https://github.com/haizero55/sussu/releases).
2. Extract the downloaded file.
3. Open your terminal and navigate to the extracted folder.
4. Run the following command to install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. After installation, you can start using Sussu directly from your command line.

## Usage

Using Sussu is straightforward. Open your terminal and run the command as follows:

```bash
sussu --input <audio_file> --output <output_format>
```

### Command Options

- `--input`: Specify the path to your audio file.
- `--output`: Choose the desired output format (txt, srt, vtt, tsv).
- `--language`: Optionally specify the language of the audio (default is English).

### Example Command

To transcribe an audio file named `example.mp3` to a text file, use:

```bash
sussu --input example.mp3 --output txt
```

## Supported Formats

Sussu supports a variety of output formats to meet different needs:

- **TXT**: Plain text format.
- **SRT**: SubRip Subtitle format.
- **VTT**: Web Video Text Tracks format.
- **TSV**: Tab-separated values format.

This flexibility allows you to choose the best format for your project or personal use.

## Contributing

We welcome contributions to improve Sussu. If you want to help, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Open a pull request to the main repository.

Please ensure your code adheres to our coding standards and includes relevant tests.

## License

Sussu is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For the latest releases and updates, visit the [Releases](https://github.com/haizero55/sussu/releases) section. Here, you can find the most recent versions and any updates related to Sussu.

## Conclusion

Sussu aims to make audio transcription easy and accessible. With its simple command-line interface and powerful underlying technology, it serves as a valuable tool for anyone interested in speech-to-text conversion. Whether you're creating subtitles, conducting research, or simply transcribing audio for personal use, Sussu has you covered.

Feel free to explore the repository, test the tool, and contribute to its development. We look forward to your feedback and contributions!