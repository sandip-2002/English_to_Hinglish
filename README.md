# English to Hinglish Translator

This repository contains a Python code script (Jupyter Notebook) that translates English sentences to Hinglish. It utilizes the Hugging Face Transformers library for machine translation. The code also processes nouns and verbs within the input sentences.

## Requirements

- Python 3.6+
- Jupyter Notebook
- Transformers library (`pip install transformers`)
- NLTK library (`pip install nltk`)
- SentencePiece library (`pip install sentencepiece`)

## Installation

1. Clone the repository to your local machine.

```bash
git clone https://github.com/sandip-2002/English_to_Hinglish.git
cd English_to_Hinglish
```

2. Create a virtual environment and install the required packages:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```
3. Start a Jupyter Notebook server:
```bash
jupyter notebook
```
## Usage
1.Running the Model

2.Open the Jupyter Notebook file English_to_Hinglish_Translator.ipynb.

3.Ensure you have Jupyter Notebook installed, and the required Python packages are installed in your virtual environment.

3. Run the code cells in the Jupyter Notebook to translate English sentences to Hinglish.

4.The output translations will be displayed within the notebook, and the Hinglish translations will be generated and printed.

## Evaluating Model Performance
1. Collect reference translations for the sentences to be evaluated.
2. Generate candidate translations using your machine translation model.
3. For each sentence:
   a. Tokenize the reference and candidate translations.
   b. Calculate the BLEU score for the candidate translation compared to the reference translations.
   c. Use a smoothing function to handle discrepancies in n-gram counts.
4. Calculate the average BLEU score across all sentences.
5. Interpret the BLEU scores: Higher scores indicate better translation quality.
6. Use BLEU scores to assess and potentially improve your machine translation model.


## Output
The output translations for the provided example sentences are saved in the [output.txt](https://github.com/sandip-2002/English_to_Hinglish/blob/main/Output.txt) file.

## Examples
Here are some example sentences that you can translate:

"Definitely share your feedback in the comment section."
"So even if it's a big video, I will clearly mention all the products."
"I was waiting for my bag."

## Credits
This code uses the [Hugging Face Transformers](https://huggingface.co/docs/transformers/tasks/translation) library for machine translation.
