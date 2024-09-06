**Official Repository of the Paper**: **_HuLLMI: Human vs. LLM Identification with Explainability_**
Welcome to the official repository for the paper _"HULLMI: Human vs. LLM Identification with Explainability."_ This repository contains the datasets used in our study, including our self-curated dataset, as well as the code used for various machine learning models.

Repository Contents
**Datasets**: The datasets used for our study, including the curated dataset, are available in this repository.

**Traditional Machine Learning Models**:

The code for traditional machine learning models (excluding LSTM) can be found in the HuLLMI_Paper_ML_Traditional_Model.ipynb notebook, which you can access by downloading the provided ZIP file.

**Advance Deep Learning Models**:

For LSTM, T5-Sentinel, and RoBERTa-Sentinel models, refer to the LSTM_T5_Sentinel_and_Roberta_Sentinel_T5_Sentinel_ROC_DET.ipynb notebook.
For detailed code snippets of the RoBERTa-Sentinel model, check the HuLLMI_Roberta_Sentinel_.ipynb notebook.
Plot Generation:

We've included additional code snippets used for plot generation. Please review the relevant sections for more details.
Note: To view the LIME plots from our study, please open the notebooks in Google Colab or Jupyter Notebook.

---------------------------**ABSTRACT**--------------------------------

As LLMs become increasingly proficient at producing human-like responses, there has been a rise of
academic and industrial pursuits dedicated to flagging a given piece of text as "human" or "AI". Most
of these pursuits involve modern NLP detectors like T5-Sentinel and RoBERTa-Sentinel, without
paying too much attention to issues of interpretability and explainability of these models. In our study,
we provide a comprehensive analysis which shows that traditional ML models (Naive-Bayes, MLP,
Random Forests, XGBoost) perform as well as modern NLP detectors, in human vs AI text detection.
We achieve this by implementing a robust testing procedure on diverse datasets, including both
curated corpora and real-world samples. Subsequently, by employing explainable AI techniques like
LIME, we uncover parts of the input which contribute most to a model’s prediction, providing insights
into the detection process. Our study contributes to the growing need for developing production level
LLM detection tools, which can leverage a wide range of traditional as well as modern NLP detectors
we propose. Finally, the LIME techniques we demonstrate also have the potential to equip these
detection tools with interpretability analysis features, making them more reliable and trustworthy in
various domains like education, healthcare and media.
-----------------------------------------------------------------------------------------------------


This work is Collectively Done by Prathamesh Dinesh Joshi, Sahil Pocker, Raj Abhijit Dandekar, Rajat Dandekar and Sreedath Panat
