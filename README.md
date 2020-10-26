# AUEB MLCA - Deep Learning Text Classification

We are three ambitious students of the [Master of Science in Business Analytics programme at AUEB](http://analytics.aueb.gr/), who are called upon to complete a text classification problem related to [Sustainable Development Goals (SDGs)](https://sdgs.un.org/goals). 

The main idea is to train a Neural Network with pre-classified data and create an algorithmic model so that, by entering new data, we can achieve the greatest predictability in new and future publications.

Initially, in order to run either of the 2 deep learning notebooks you should produce the datasets. You have two options:

- You can directly download the two CSVs and run the corresponding classification notebooks, from this [link](https://github.com/Nightherald/Deep-Learning-Annotation/tree/main/parser_eda_extract/Dataset) (we already uploaded them on Github)
- You can download the [parser_eda_extract.ipynb file](https://github.com/Nightherald/Deep-Learning-Annotation/blob/main/parser_eda_extract/parser_eda_extract.ipynb), along with the [research theme folder](https://github.com/Nightherald/Deep-Learning-Annotation/tree/main/parser_eda_extract/research_theme)

The original raw data is included in the **research theme** folder. Before getting to the analysis, you should also unzip the **documents** folder in order for the **parser_eda_extract.ipynb** to perform correctly. Two csv files will be extracted, so that you can import them to their respective notebooks - one for binary and one for multiclass classification purposes. The third notebooks is used for prediction purposes. Notebooks are fully commented, however you can always look at the report for further explanations. 

On the same note you should also download the heldout csv with the same options as before:

- You can directly download the CSV and run the corresponding classification notebook, from this [link](https://github.com/Nightherald/Deep-Learning-Annotation/tree/main/heldout_parser_eda_extract/Dataset) (we already uploaded it on Github)
- You can download the [heldout_parser_eda_extract.ipynb file](https://github.com/Nightherald/Deep-Learning-Annotation/blob/main/heldout_parser_eda_extract/heldout_parser_eda_extract.ipynb), along with the [research theme folder](https://github.com/Nightherald/Deep-Learning-Annotation/tree/main/heldout_parser_eda_extract/research_theme)

Tip: Run the jupyter notebooks in Google Colab to enhance performance

### Keep in Mind
Due to the demanding time restrictions we had to make 2 compromises:

1. The metrics (as well as the [Binary Saved Models](https://github.com/Nightherald/Deep-Learning-Annotation/tree/main/Binary%20Saved%20Models) files) of the binary classification deep learning models differ from those presented in the [mlca-annotation-report.pdf](https://github.com/Nightherald/Deep-Learning-Annotation/blob/main/mlca-annotation-report.pdf). We had to re-calculate overall predictions (initially we calculated a prediction per model) on a heldout dataset at a later time, so we had to rerun the notebooks. The [group1_research_theme_binary.csv](https://github.com/Nightherald/Deep-Learning-Annotation/blob/main/group1_research_theme_binary.csv) contains 92 predictions based on our original best trained model (a CNN model with self-trained embeddings) at the time.

2. We planned to transfer the insights gained from our Binary Classification deep learning models (concerning the hyper-parameter variations) and proceed with Multiclass Classification. Alas, that was not possible and since we were not satisfied with the final notebook, the Multiclass Classification deep learning models are more limited in scope.


Enjoy! 

- [Lianos Alexandros](https://www.linkedin.com/in/alexandros-lianos-679850150/)
- [Marinos Efstratios](https://www.linkedin.com/in/efstratiosmarinos/)
- [Lydia Papanikou](https://www.linkedin.com/in/lydia-papanikou-59500067/)
