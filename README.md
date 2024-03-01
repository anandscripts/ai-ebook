
# Ebook Generation with OpenAI

This project utilizes OpenAI's powerful language models to generate an entire ebook on a given topic. The ebook includes a predefined title, outline, chapters with subchapters, a disclaimer, and a conclusion. The content is dynamically generated using OpenAI's text-davinci-003 engine, providing unique and coherent text for each section.

## Getting Started

### Prerequisites

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- OpenAI Python library (`openai`)
- `docx` library for working with Word documents

You can install the required Python libraries using the following command:

```bash
pip install -r requirements.txt
```

### Configuration

1. Obtain an API key from OpenAI by following their [documentation](https://beta.openai.com/docs/).
2. Set your API key in the script: `openai.api_key = "YOUR-API-KEY"`
3. Specify the desired folder path (`user_path`) and ebook title (`title`) in the script.

## Usage

1. Run the script `ebook_generator.py`.
2. The script will prompt OpenAI to generate an outline, disclaimer, chapters, and conclusion for the ebook.
3. The resulting ebook will be saved in the specified folder with the title provided.

## Customization

- Adjust the engine, token limits, and other parameters in the OpenAI requests to fine-tune the text generation.
- Customize the document styling, margins, and fonts according to your preferences.
- Explore other OpenAI models for different writing styles and outputs.

## Acknowledgments

- [OpenAI](https://www.openai.com/) for providing access to cutting-edge language models.
- [python-docx](https://python-docx.readthedocs.io/) for the library used to create Word documents in Python.

Feel free to contribute, report issues, or suggest improvements by creating a pull request or issue.
