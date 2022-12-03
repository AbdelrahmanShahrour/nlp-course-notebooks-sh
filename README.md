# ShAI NLP Course Notebooks

This repository contains the notebooks for ShAI's Natural Language Processing course

## Content
| Notebook                                                                                  | Chapter | Section | Description                                                   | Exercise |
| ----------------------------------------------------------------------------------------- | ------- | ------- | ------------------------------------------------------------- | -------- |
| [Pytorch Basics 1](PyTorch-Basics-1.ipynb)                                                | 0       | 3       | PyTorch tensor creation and basic operations                  |          |
| [Pytorch Basics 2](PyTorch-Basics-2.ipynb)                                                | 0       | 3       | Creating neural networks with PyTorch                         |          |
| [Pytorch Basics Exercise](PyTorch-Basics-Exercise.ipynb)                                  | 0       | 3       | Practice neural networks with PyTorch                         | ✔️        |
| [Regex Basics](Regular-Expressions-Basics.ipynb)                                          | 0       | 4       | Introduction to Regular Expressions                           |          |
| [Text Preprocessing](Text-Preprocessing.ipynb)                                            | 1       | all     | Apply preprocessing to text                                   | ✔️        |
| [Text Tokenization](Text-Vectorization-Tokenization.ipynb)                                | 2       | 1       | Tokenize text by word or character                            | ✔️        |
| [Text Encoding](Text-Vectorization-Encoding.ipynb)                                        | 2       | 2,3     | Encode text by onehot and tfidf                               | ✔️        |
| [Word Embeddings (Word2Vec)](Text-Vectorization-Word2Vec.ipynb)                           | 2       | 4       | Implement Word2Vec to generate word embeddings                |          |
| [Text Classification](Text-Classification-RNN.ipynb)                                      | 3       |         | Implement Sentiment Analysis with RNN                         | ✔️        |
| [Text Translation](Text-Translation.ipynb)                                                | 4       | 1       | RNN Seq2Seq for translation                                   |          |
| [Text Translation with Attention](Text-Translation-Attention.ipynb)                       | 4       | 2       | Add Bahdanau attention  to Seq2Seq model                      |          |
| [Text Translation with Transformer](Text-Translation-Transformer.ipynb)                   | 4       | 3       | Introduction of Transformer model for translation             |          |
| [Text Classification with HuggingFace transfomers](Text-Classification-HuggingFace.ipynb) | 6       |         | Use Huggingface pretrainedtransformers for sentiment analysis |          |



## Instructions

1. Create a virtual envrionment

   ```bash
	python -m venv venv
   ```

2. Activate the environment and install the required packages
   ```bash
	source venv/bin/activate
	pip3 install -r requirements.txt
   ```

3. Run Jupyter Notebook sever
	```bash
	jupyter notebook
	```
