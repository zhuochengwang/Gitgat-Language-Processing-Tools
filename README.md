# SRT File Translator with DeepL

Welcome to the SRT File Translator script repository! This Python script offers a convenient solution for translating SRT (SubRip Subtitle) files from one language to another using the powerful DeepL translation service. Whether you're working on video subtitles or multilingual content, this script simplifies the translation process and ensures accuracy in your subtitles.

## Features

- **Translation with DeepL:** Utilizes the DeepL translation service to provide high-quality and accurate translations.

- **SRT File Support:** Translates SRT files commonly used for video subtitles.

- **Preservation of Format:** Maintains the original SRT format, including timestamps and line numbering.

- **Customizable:** Easily adapt the script to your specific translation needs, including target languages and DeepL API authentication.

## Getting Started

1. Clone this repository to your local machine.

2. Replace the `auth_key` variable with your DeepL API key. You can obtain an API key from the DeepL website.

3. Specify the `folder_path` variable to point to the folder containing your SRT files that need translation.

4. Set the `output_folder_path` variable to the directory where you want to save the translated SRT files.

5. Define the `target_language` variable with the language code of your target language (e.g., "EN" for English).

6. Run the script, and it will automatically translate the SRT files in the specified folder and save the translated versions in the output directory.

## Example

```python
# Example configuration
auth_key = "your-deepl-api-auth-key"  # Replace with your DeepL API key
folder_path = "/path/to/your/folder"  # Replace with your folder path containing SRT files
output_folder_path = "/path/to/your/output/folder"  # Replace with the path where you want to save translated SRT files
target_language = "EN"  # Replace with your target language code

# Translate SRT files
translate_all_srt_in_folder(folder_path, output_folder_path, target_language, auth_key)
```

## License

This script is released under the [GNU General Public License (GPL) version 3.0](LICENSE), ensuring its open-source nature and the freedom to use, modify, and distribute it.

---

Feel free to use this introduction to showcase your SRT File Translator script on GitHub. You can customize it further to add specific details or instructions as needed.
