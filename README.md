# DnD Character Backstory Generator

A Streamlit application that generates rich Dungeons & Dragons character backstories and Adobe Firefly art prompts to visually bring your characters to life.

## Overview

This project combines the power of large language models and AI image generation to help Dungeons & Dragons players create compelling character backstories with accompanying visual representations. By leveraging few-shot prompting techniques and the DeepSeek Chat model, users can quickly generate unique character concepts and then visualize them using Adobe Firefly.


## Technical Implementation

- **Frontend**: Streamlit application for an interactive web interface
- **AI Model**: DeepSeek Chat (deepseek/deepseek-chat) for text generation
- **Prompting Technique**: Few-shot prompting with curated examples of high-quality D&D character backstories

## Getting Started

### Prerequisites

- Python 3.8+
- Streamlit
- DeepSeek API access
- Internet connection for Adobe Firefly integration

### Installation

```bash
# Clone the repository
git clone https://github.com/jeremyhung22/dnd-character-generator.git
cd dnd-character-generator

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

### Usage

1. Open the application in your web browser :  https://genai-project1.streamlit.app/
2. Type in character attributes
3. Click "Submit" to create a character background

## Resources

- [Adobe Firefly](https://www.adobe.com/products/firefly.html)
- [DeepSeek Chat Documentation](https://github.com/deepseek-ai/DeepSeek-LLM)
- [Streamlit Documentation](https://docs.streamlit.io/)
- [D&D 5e SRD](https://dnd.wizards.com/resources/systems-reference-document)

## License

This project is licensed under the MIT License - see the LICENSE file for details.
