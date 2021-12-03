## Team: 6
## Team members: 

1.   Balasubramanian, Karthik
2.   Harnett, Rait
3.   Jones, Ben
4.   Kozin, Igor N
5.   Loffredo, Dom

# Overview

Our approach was to investigate well known techniques to visualize the Child Mind Institute data. We focused on the description parts on a selection of the data:

*   CrisisLogger: `Data/CrisisLogger/crisislogger.csv`
*   ProlificAcademic: `Data/ProlificAcademic/updated_data/April_21/CRISIS_Adult_April_2021.csv`, `Data/ProlificAcademic/updated_data/April_21/CRISIS_Parent_April_2021.csv`

We show how we used the following techniques:

*   Clustering documents with TFIDF and KMeans.
*   A word cloud generator.
*   Pre-trained BERT model to predict sentiment.
*   Using ``spaCy`` to analyze transcriptions in the CrisisLogger data.

We also tested the usability of T0pp pretrained model: 
https://huggingface.co/bigscience/T0pp https://huggingface.co/transformers/installation.html (see [ml_for_good_T0pp.ipynb](https://github.com/raitharnett/ML-for-Good-Hackathon/blob/main/ml_for_good_T0pp.ipynb) for details)

# Files
Our submission is contained in [ml_for_good.ipynb](https://github.com/raitharnett/ML-for-Good-Hackathon/blob/main/ml_for_good.ipynb) and due to resource requirements of the pre-trained BERT model was run on [Google Colab](https://colab.research.google.com/). 
The T0pp pretrained model investigation was very resource intensive and needed to be run in a separate notebook, [ml_for_good_T0pp.ipynb](https://github.com/raitharnett/ML-for-Good-Hackathon/blob/main/ml_for_good_T0pp.ipynb).
