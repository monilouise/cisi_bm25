# Building a Simple Information Retrieval System using BM25 and GPT-3 and evaluated in the CISI collection

Author: Monique Louise de Barros Monteiro - moniquelouise@gmailcom

This experiment aims to validate the BM25 algorithm as a baseline for information retrieval (IR) on the CISI dataset, a benchmark aimed at evaluating IR algorithms. Additionally, the ChatGPT agent was employed throughout the experiment stages to obtain preliminary information.


In this repository, the following items are included:

* [Queries_ChatGPT.ipynb](https://github.com/monilouise/cisi_bm25/blob/main/Queries_ChatGPT.ipynb): A file containing transcripts of the main interactions with ChatGPT, as well as an analysis of some information provided by the agent.
* [CISI_BM25_Rank_BM25.ipynb](https://github.com/monilouise/cisi_bm25/blob/main/CISI_BM25_Rank_BM25.ipynb): A Jupyter notebook file (.ipynb) with the experiment performed using the Rank BM25 library.
* [CISI_BM25_Pyserini.ipynb](https://github.com/monilouise/cisi_bm25/blob/main/CISI_BM25_Pyserini.ipynb): A Jupyter notebook file (.ipynb) with the experiment performed using the Pyserini library.
* [report.pdf](https://github.com/monilouise/cisi_bm25/blob/main/report.pdf): A brief report describing the implementation details, results, how to test the IR system and how chatGPT helped with the project.

## Instructions

In order to run the experiments, it's only necessary to upload the Jupyter notebooks (ISI_BM25_Rank_BM25.ipynb and CISI_BM25_Pyserini.ipynb) and the dataset files (CISI.ALL, CISI.QRY and CISI.REL ) to [Google Colab](https://colab.research.google.com).
