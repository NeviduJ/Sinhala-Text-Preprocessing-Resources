# Sinhala-Text-Preprocessing-Resources

A comprehensive repository containing resources, scripts, and notebooks for preprocessing Sinhala text, with a focus on the Sri Lanka Constitution in Sinhala. This project demonstrates various text preprocessing techniques including tokenization, stemming, suffix removal, word embeddings, and vectorization.

## 🚀 Project Overview

This repository serves as a research and development platform for Sinhala text preprocessing tasks. The main corpus is the Sri Lanka Constitution in Sinhala, which has been processed through multiple preprocessing pipelines to create various linguistic resources and demonstrate different text preprocessing approaches.

## 📁 Repository Structure

### 📓 Jupyter Notebooks
- **`Sinh_Word2Vec.ipynb`** - Trains and analyzes Word2Vec embeddings for Sinhala text
- **`Suffix_removal.ipynb`** - Demonstrates suffix removal techniques for Sinhala words
- **`TF-IDF_Vectorization.ipynb`** - Performs TF-IDF vectorization on Sinhala documents
- **`Create_PDF.ipynb`** - Generates PDF documents from processed text
- **`Electra_Trained_Tokenizer.ipynb`** - Experiments with Electra tokenizer for Sinhala
- **`Llama_3.1.ipynb`** - Experiments with Llama 3.1 language model for Sinhala

### 🐍 Python Scripts
- **`make_stem_dictionary.py`** - Creates a comprehensive stem dictionary from Sinhala text

### 📊 Data Files
- **`Sri Lanka Constitution - Sinhala.pdf`** - Original Sinhala constitution document
- **`Sri Lanka Constitution - Sinhala - Suffix Removed.pdf`** - Constitution with suffixes removed
- **`Sri Lanka Constitution-Sinhala.txt`** - Raw text version of the constitution
- **`Sri Lanka Constitution-Sinhala_Suff_Rem.txt`** - Suffix-removed text version
- **`Sri Lanka Constitution-Sinhala Tokenized.txt`** - Tokenized version of the constitution
- **`stem_dictionary.txt`** - Comprehensive list of Sinhala word stems
- **`suffixes_list.txt`** - List of suffixes used for removal operations
- **`Word_Embeddings_W2V.pth`** - Pretrained Word2Vec embeddings for Sinhala
- **`unicode.pdf`** - Unicode reference for Sinhala characters

### 🔧 Tokenizer Resources
- **`Sinhala_Tokenzier/`** - Directory containing:
  - `tokenizer_config.json` - Tokenizer configuration
  - `vocab.txt` - Vocabulary file
  - `tokenizer.json` - Tokenizer model
  - `special_tokens_map.json` - Special tokens mapping

### 📄 Text Processing
- **`Text_files/`** - Contains 157 page-wise processed text files of the constitution

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- pip package manager

### Required Libraries
```bash
pip install jupyter
pip install gensim
pip install nltk
pip install scikit-learn
pip install reportlab
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
```

## 📖 Usage Guide

### 1. Getting Started
1. Clone this repository
2. Install the required dependencies
3. Launch Jupyter Notebook: `jupyter notebook`

### 2. Text Preprocessing Workflow
- Start with **`Suffix_removal.ipynb`** to understand text preprocessing
- Use **`Sinh_Word2Vec.ipynb`** for word embedding analysis
- Apply **`TF-IDF_Vectorization.ipynb`** for document vectorization
- Generate reports with **`Create_PDF.ipynb`**

### 3. Custom Preprocessing
- Modify **`make_stem_dictionary.py`** for custom dictionary creation
- Use the provided tokenizer resources for consistent text processing
- Leverage the stem dictionary and suffix lists for text analysis

## 🔬 Text Preprocessing Applications

This repository supports various text preprocessing research areas:
- **Morphological Analysis** - Suffix removal and stemming
- **Word Embeddings** - Word2Vec training and analysis
- **Document Vectorization** - TF-IDF and other vectorization techniques
- **Tokenization** - Custom tokenizer development for Sinhala
- **Language Modeling** - Experiments with modern language models

## 📈 Output Examples

The project generates several types of outputs:
- **PDF Reports** - Formatted analysis results
- **Word Embeddings** - Trained Word2Vec models
- **Processed Text** - Cleaned and tokenized text files
- **Linguistic Resources** - Stem dictionaries and suffix lists

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Submit issues and feature requests
- Contribute improvements to existing notebooks
- Add new preprocessing techniques
- Enhance documentation

## 📄 License

This project is open source and available under appropriate licensing terms.

## 📞 Contact

For questions or collaboration opportunities, please open an issue in this repository.

---

*Last updated: December 2024*
