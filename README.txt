Authors:
Alexandre Crivellari 902064
Andrea Muscio 889901

How to run the Notebook:
We recommend to download the complete GitHub Repository available at https://github.com/alexcri90/LIAR_TextMining_Bicocca.git

The complete datasets (training, testing and validation) are available in the following Google Drive Folder, available to all Università Bicocca users: https://drive.google.com/drive/folders/1m2APXYwnzk6eixVrtQSxyClyYydCtoPU?usp=sharing
The datasets MUST be stored in the same directory as the TM_Notebook file for reproducibility purposes.

The main jupyter notebook to run is "TM_Notebook.ipynb". All dependencies are commented out in the first cell, in case the user needs to make use of some libraries (imported later in the following cell) they should be uncommented before running.

The folder also contains a "lda_topics.html" file, which opens an interactive HTML page for navigating through the topics discovered during the Topic Modeling task of the project.

IMPORTANT NOTE ABOUT PYTORCH: the library "torch" (Pytorch) refers to its version CUDA 12.1. For computational performance, a dedicated GPU nVidia RTX 4070 Ti has been used for reducing training time. 