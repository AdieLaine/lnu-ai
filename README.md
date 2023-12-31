# <span style="color: Crimson;">Lnu-AI</span>: An Indigenous AI System 🪶
[![GitHub License](https://img.shields.io/github/license/AdieLaine/lnu-ai)](https://github.com/AdieLaine/lnu-ai/blob/main/LICENSE)
<p align="center">
  <img src="./images/word-lines.png"/>
</p>
Lnu-AI is an Artificial Intelligence system developed to serve as a bridge between the Mi'kmaq language and AI. This platform is rooted in the deep commitment to cultural preservation, leveraging modern technologies like machine learning and natural language processing to aid in the revitalization of the Mi'kmaq language.

---



## <span style="color: white;">Table of Contents</span>
- [Project Statement](docs/projectstatement.md)
- [Features](#features)
  - [Lnu-AI Chat](docs/chat.md)
  - [Storyteller](docs/story.md)
  - [Examine Words](docs/words.md)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---
## <span style="color: white;">Getting Started</span>
### <span style="color: white;">Prerequisites</span>
- Python 3.7+
- pip
- OpenAI API Key

### <span style="color: white;">Installation</span>
1. Clone the repo:

   `git clone https://github.com/AdieLaine/lnu-ai.git`

2. Install Python packages:

   `pip install -r requirements.txt`

3. Copy the .env.example file and create a new .env file.
4. Replace "your-openai-key" in the .env file with your actual OpenAI API Key.
5. If required, replace other variables in the .env file based on your configuration.

### <span style="color: white;">Audio Files</span> - Important Note

1. Because these audio files are sourced from a resource that has expressed a common creative license, we want to honor that and so we will only include a small sample of the audio files. This allows the program to still demonstrate the features within the Sound of Words function. If you would like to access the full audio files, please contact us and we will provide you with the information to access the full audio files.

2. For demonstrative purposes, we've kept files for any Mi'kmaq word found that begins with the letter 'Q or q'. These words will play the audio file and will provide the sound of words visualization.

### <span style="color: white;">Data Files</span> - Important Note

1. Due to the size of: trained_data_embeddings.json and word_details_embeddings.json we have decided to offer them as a direct download. Those two data files are stored in a Google Drive folder. You can access the folder [here](https://drive.google.com/drive/folders/1XvBdEu7kn9vr7bn3eJOUuLPeEK4x-DY4?usp=drive_link).

2. Simply download the folder and place it in the root directory of the project. The project will automatically detect the folder and use the data files. Be sure to check the Readme file in the folder for more information.

3. We understand that this is not the most ideal solution, but we are working on a better solution for the future.

---

## <span style="color: white;">Usage</span>
1. Ensure you are in the project directory and run: `streamlit run src/lnu-ai.py`
2. Open the link in your browser:  streamlit run src/lnu-ai.py
3. After executing the above command, open the link displayed in the terminal in your web browser: Local URL: http://localhost:8501
---

## <span style="color: white;">Contribution Guidelines</span>

We welcome contributions, issues, and feature requests! If you're considering significant changes, kindly open an issue first to discuss what you would like to change.

---

## <span style="color: white;">License</span>
This project is licensed under the terms of the [MIT license](https://github.com/AdieLaine/lnu-ai/blob/main/LICENSE).

---

## <span style="color: white;">Acknowledgements</span>
The Lnu-AI project honors the timeless art of storytelling, keeping the flame of tradition alive and preserving the rhythmic beauty of Mi'kmaq words. Lnu-AI is my heartfelt gift to the Mi'kmaq people, a testament to our shared heritage, and a vital step towards a future where technology and tradition intersect gracefully, celebrating and honoring the richness of cultural diversity.

We would like to acknowledge [Mi'gmaq-Mi'kmaq Online](https://mikmaqonline.org/) for consolidating Listuguj Mi'kmaq translations.

Lnu-AI was born at the crossroads of GPT-4 API and the insatiable curiosity to be creative. We extend out thanks to[OpenAI](https://openai.com/) for providing the API solution that was critical in the pre-training and fine-tune process.

---

Developed by [Madie Laine](https://twitter.com/justmadielaine)