
# Audio Transcription with Speaker Differentiation

## Overview
This project uses the OpenAI Whisper model to transcribe audio files and differentiate between speakers. The transcription includes timestamps for long audio files.

---

## Features
- Automatic speech recognition (ASR) using OpenAI Whisper.
- Speaker differentiation for multi-speaker conversations.
- Handles long audio files with timestamps for transcription.

---

## Installation

### Prerequisites
- Python 3.8+
- API keys for OpenAI and Hugging Face.

### Setup
1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your environment variables**
   Copy the `.env.example` file and update it with your API keys:
   ```bash
   cp .env.example .env
   ```
   Update `.env`:
   ```
   OPENAI_API_KEY=your_openai_api_key
   HUGGINGFACE_API_KEY=your_huggingface_api_key
   ```

---

## Usage

1. **Add your audio file**
   Place your audio file in the `sample_files` directory or use the provided `example_audio.mp3` file.

2. **Run the script**
   ```bash
   python fichier.py
   ```

3. **Output**
   - Transcription with speaker differentiation saved to `transcription_with_speakers_v3.txt`.
   - Meeting notes saved to `notes_with_speakers_v3.txt`.

---

## Repository Structure
```
/project-root
  - fichier.py                # Main script
  - README.md                 # Project documentation
  - .env.example              # Template for environment variables
  - requirements.txt          # Python dependencies
  - LICENSE                   # License file
  /sample_files               # Example audio files
    - example_audio.mp3       # Sample MP3 file
  /tests                      # Unit tests (if applicable)
    - test_fichier.py
```

---

## Sample Output

### Transcription Example
```
[Speaker 1]
Hello, everyone. Welcome to today's meeting.

[Speaker 2]
Thank you. Let’s get started with the agenda.
```

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contributing
Feel free to open issues or submit pull requests for bug fixes or feature requests.

---

## Contact
For any inquiries or feedback, please reach out to [your email or GitHub profile].
