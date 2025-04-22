# Vector Representation & Similarity Analysis Notebook

This repository contains a Jupyter notebook that explores vector representations of words using pre-trained GloVe embeddings. It includes multiple text processing utilities such as cosine similarity, basic pre-processing and file-based vocab/vector manipulation.

---

## 📘 About the Notebook

This notebook demonstrates:
- How to load and use GloVe embeddings
- How to create and store vocabulary and vector mappings
- How to preprocess text data and remove stopwords
- Saving and loading `.txt` vector files (`vocab.txt` and `tVector.txt`)
- How to gain insights from word emebddings
- Implmenting a model for classifying reviews

It is primarily intended for educational use and includes selected utility functions sourced from university material. These components are acknowledged and used only as part of the academic learning process.

---

## 📂 Files Required

Before running the notebook, ensure you have the following files:

- `Data.csv`: The input dataset.
- `stopwords_en.txt`: List of English stopwords.

These files are used to load and save vocabulary and word vectors and provide context for processing.

---

## 🧠 GloVe Model Handling

The notebook **automatically downloads** the GloVe model file (`glove.6B.50d.txt`) from a Hugging Face repository:

🔗 [Download Link (Hugging Face)](https://huggingface.co/datasets/Jay-Mayekar/glove-vectors/resolve/main/glove.6B.50d.txt)

You do **not** need to manually download or store the file. The notebook will fetch it fresh on each run and use it as a regular `.txt` file.

---

## ▶️ How to Run

1. Clone this repository or download the entire directory:
   ```bash
   git clone https://github.com/JayZxD/Vector-NLP-Project.git

2. Ensure the following dependencies are installed:

 - numpy
 - pandas
 - nltk
 - sklearn
 - requests

3. Run the notebook:
   ```bash
   jupyter notebook Main.ipynb

## ⚠️ Disclaimer

Some functions in this notebook are derived from university lecture materials. They are used here purely for educational purposes, and no ownership is claimed for those portions of code.

## 📬 Author
[Jay Mayekar](https://www.linkedin.com/in/jay-mayekar25/)





