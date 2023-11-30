# Gitgat-Language-Processing-Tools
Welcome to the Gitgat Language Processing Tools repository! This repository offers a set of compact and efficient Python scripts for language processing and text cleaning tasks. These tools are designed to simplify common text-related challenges in your projects.
Certainly! Here's an introduction that you can use to present your script on GitHub:

---

# Text Line Segmentation for Portuguese Texts

This Python script provides a convenient way to segment long lines of Portuguese text while preserving the original meaning and format. It's particularly useful for maintaining readability and adherence to character limits in text-based applications and documents.

## Overview

When working with Portuguese text, it's common to encounter long sentences or lines that may exceed a desired character limit. In such cases, it's essential to segment the text effectively to ensure that it remains comprehensible. This script offers a solution by leveraging a combination of primary and secondary breakpoints to split long lines.

## Features

- **Retains Commas:** The script retains commas as primary breakpoints while splitting text, ensuring that the output maintains the same format as the input.

- **Enhanced Linguistic Rules:** The script includes enhanced linguistic rules for Portuguese, such as recognizing common conjunctions, punctuation marks, phrasal patterns, and clause structures that provide natural points for line segmentation.

- **Balanced Line Lengths:** It balances line lengths when segmenting text, improving the overall readability of the segmented content.

## Usage

To use the script, simply provide the input text files containing long lines of Portuguese text. The script will process these files, segment the lines as per the defined rules, and save the segmented content into output files.

## Getting Started

1. Clone this repository to your local machine.
2. Modify the `input_folder_path` and `output_folder_path` variables in the script to specify your input and output directories.
3. Adjust the `max_chars` variable to set your desired character limit for each line.
4. Run the script, and it will segment the text lines in your input files, preserving the original format.

## Example

```python
# Usage
input_folder_path = '/path/to/your/input/folder'
output_folder_path = '/path/to/your/output/folder'
max_chars = 70
segment_all_txt_files_in_folder(input_folder_path, output_folder_path, max_chars)
```

## Contributions

Contributions, bug reports, and suggestions are welcome! Feel free to open issues and pull requests to improve the script's functionality.

## License

This repository is released under the GNU General Public License (GPL) version 3.0.

---

Feel free to customize this introduction to provide more specific details about your project, and don't forget to include a license file (e.g., LICENSE) if you haven't already. This introduction provides a starting point for your GitHub repository's README.md file.
