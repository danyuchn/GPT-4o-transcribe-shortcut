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

You can also change the `model` parameter to `gpt‑4o‑mini‑transcribe` or `whisper‑1` for alternative transcription backends.

---

## Additional Resources

For more detailed API configuration instructions, please refer to [OpenAI Speech-to-Text API Guide](https://platform.openai.com/docs/guides/speech-to-text).

---

**Acknowledgments**

Special thanks to GPT o4-mini-high and o4‑mini for their invaluable assistance in crafting this shortcut.
