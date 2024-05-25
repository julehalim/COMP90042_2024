Tue9am_Group6
===============

Final Model (Bi-encoder + Sequential)
----------

Our final, best performing model is the bi-encoder model for evidence retrieval and a sequential model for claim classification named Tue9am_Group6.ipynb. The log output for eval.py is outputted within the model's jupyter notebook itself.

Transformer Model
-----

Our transformer model consists of two parts, the evidence retrieval (Transformer_Evidence_Retrieval.ipynb) file and the label classification (Transformer_Label_Classification.ipynb) file. The evidence retrieval file has to be run to create the file for label classification. Label classification also has commented out code to use the bi-directional LSTM model's retrieved evidences (in the file, these have comments relating to using Noah's retrieved evidences).

Bi-Directional LSTM
-----

Our bi-directional LSTM model file is called noah_COMP90042_Project_2024.ipynb.
