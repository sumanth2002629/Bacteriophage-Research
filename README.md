# Data
The data used for the work is available at [a link](https://drive.google.com/drive/folders/1XLgpgSP6CIS8XshQqqI1Z2C2Db07Lx3T?usp=sharing). After downloading the data, the appropriate data path should be given in **do_prediction**
and **do_training** functions in every notebook.

# Structure
The code is organised in three folders namely CNN, DNA_BERT and combined_embeddings.

- CNN contains two notebooks, onehot.ipynb has the code to encode the DNA sequences and CNN.ipynb contains the code that trains a CNN on the one-hot encodings.
- DNA_BERT also contains two notebooks, DNA_BERT2.ipynb has the code to obtain the DNA embeddings from DNA_BERT2 and DNA_embeddings.ipynb contains the code that trains an ANN on the DNA embeddings.
- combined_embeddings contains a notebook called combine_embeddings.ipynb that trains a neural network on the combined embeddings of ProtT5 and ESM-1b.
- Lastly, protein_embeddings.ipynb contains the code for training a neural network on the protein embeddings from various protein language models.
