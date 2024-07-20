# Spanish-to-English Translator using Multi-Head Attention Transformers

## Overview

This project implements a Spanish-to-English translator using a transformer model with multi-head attention mechanisms. The model consists of one encoding layer and one decoding layer, leveraging the power of transformer architecture to perform sequence-to-sequence translation tasks.

### Key Features

- **Transformer Architecture:** Utilizes multi-head attention layers to capture complex dependencies between words in Spanish and English.
- **Single Encoding and Decoding Layer:** Focuses on one encoding layer and one decoding layer for simplicity and demonstration purposes.
- **Tokenization and Padding:** Uses TensorFlow's `Tokenizer` and `pad_sequences` for preprocessing text data.

## Installation

To set up the environment and install the necessary dependencies, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/spanish-english-translator.git
    cd spanish-english-translator
    ```

2. **Create and Activate a Virtual Environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies:**

    Ensure you have `pip` installed, then run:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare Data:**

    Ensure you have your Spanish-English parallel corpus ready. The data should be in a format suitable for training (e.g., CSV with columns for Spanish and English sentences).

2. **Train the Model:**

    Run the Cells in the Text_Translation.ipynb file

3. **Translate Sentences:**

    After training, you can use the model to translate Spanish sentences into English.

## Project Structure

- `Text_Translation.ipynb`: Script for Creation of the Transformer and translating Spanish sentences to English.
- `requirements.txt`: Lists the required Python packages.
- `README.md`: This documentation file.

## Contributing

Contributions are welcome! To contribute to this project:

1. **Fork the Repository.**
2. **Create a New Branch:**

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. **Commit Your Changes:**

    ```bash
    git add .
    git commit -m "Add feature or fix description"
    ```

4. **Push to Your Branch:**

    ```bash
    git push origin feature/your-feature-name
    ```

5. **Create a Pull Request.**


## Acknowledgments

- TensorFlow and Keras for providing powerful libraries for deep learning.
- The original creators of the transformer model.
- Developers Hutt- Youtube

