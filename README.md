# GPT‑4o Transcribe iOS Shortcut

This Apple Shortcut uses the OpenAI **gpt-4o-transcribe** model to convert recorded audio into text.

## Features
- **Audio → Text**: Upload your voice memo via multipart/form-data.
- **Custom Prompt (Adjustable)**: Enforce Traditional Chinese output for Chinese segments. 

## Installation
1. Download the `.shortcut` file.  
2. Open it in the Shortcuts App (iOS/macOS).  
3. Enter your **OpenAI API Key** in `YOUR_OPENAI_API_KEY`.

## Usage
1. Run the shortcut.  
2. Record the audio.  
3. View the transcription and choose to **Copy** or **Share**.

## Customization
You can edit the **Prompt** field inside the shortcut’s form data to:
- Adjust the language output (e.g., Simplified Chinese, English).
- Add more context or system instructions.

```bash
Prompt: "Please output Chinese parts in Traditional Chinese, keep English as-is."
