Tue9am_Group6
===============

`github-download` downloads commit comments and select issues metadata, saving the raw JSON and writing summary `.csv` files.

Final Model
----------

Our final, best performing model is the bi-encoder model named Tue9am_Group6.ipynb.

Transformer Model
-----

Our transformer model consists of two parts, the evidence retrieval (Transformer_Evidence_Retrieval.ipynb) file and the label classification (Transformer_Label_Classification.ipynb) file. The evidence retrieval file has to be run to create the file for label classification. Label classification also has commented out code to use the bi-directional LSTM model's retrieved evidences (in the file, these have comments relating to using Noah's retrieved evidences).

Bi-Directional LSTM
-----

Our bi-directional LSTM model file is called noah_COMP90042_Project_2024.ipynb.