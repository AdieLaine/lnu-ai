# Data Files Overview

This directory contains various data files that are crucial to the functioning of the Lnu-AI system. The datasets are utilized in multiple features such as language translation, semantic analysis, and the chat system. Below is a brief explanation of each file and its role within the system.


## Embedded Mi'kmaq Language Corpus

- **all_word_details.json**: This file contains comprehensive details for each word in the Mi'kmaq language, including translation, orthographic variants, pronunciation, and semantic relationships with other words.

- **embedded_word_data.json**: This file contains word embeddings for all words in the Mi'kmaq language. Word embeddings are vector representations of words that capture their meanings. The word embeddings in this file are utilized in features such as semantic analysis and the chat system.

- **mikmaq_semantic.jsonl**: This is a line-delimited JSON file that contains semantic relationships between Mi'kmaq words. Each line in the file represents a semantic relationship between two words and is part of the storytelling function.

- **trained_data.jsonl**: This line-delimited JSON file contains a collection of input-output pairs used to fine-tune the model. Each line in the file is a JSON object with an 'input' and 'output' field. This dataset is used to guide the AI's responses in the chat system.

- **trained_data_embeddings.json**: This file contains the vector representations (embeddings) of the data used to train the AI model. These embeddings capture the semantic meaning of the training data and are used to guide the model's responses.

- **word_details_embeddings.json**: This file contains embeddings for each word detail in the 'all_word_details.json' file. These embeddings capture the semantic meanings of word details and are used in various features, such as semantic analysis.

## Future Developments

In the future, we aim to continually enhance and expand these datasets by:

- Incorporating more words and phrases into the 'all_word_details.json' and 'embedded_word_data.json' files.
- Adding more training examples to the 'trained_data.jsonl' file for more nuanced and context-aware responses in the chat system.
- Integrating more semantic relationships into the 'mikmaq_semantic.jsonl' file.

As always, we welcome contributions and feedback from the community to help improve these datasets and, by extension, the functionality of the Lnu-AI system.

For more information on the project and other features of Lnu-AI, refer to the [Project Statement](../docs/ProjectStatement.md).

Developed by [Madie Laine](https://twitter.com/justmadielaine)
