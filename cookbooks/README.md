# Absolute Scoring Tutorial

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/atla-ai/selene-mini/blob/main/cookbooks/(HF_Quickstart)_Absolute_Scoring.ipynb)

This example gets you started running evals with absolute scores, and does so on a sample set from the public benchmark [FLASK](https://arxiv.org/pdf/2307.10928) dataset - a collection of **1,740 human-annotated samples from 120 NLP datasets**. Evaluators assign scores ranging from 1 to 5 for each annotated skill based on the reference (ground-truth) answer and skill-specific scoring rubrics.

Here, we evaluate the `completeness` of AI responses i.e. 'Does the response provide a sufficient explanation?'

# Hallucination Scoring Tutorial

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/atla-ai/selene-mini/blob/main/cookbooks/(HF_Quickstart)_Hallucination.ipynb)

This example gets you started detecting hallucinations, and runs over a sample set from the public benchmark [RAGTruth](https://arxiv.org/abs/2401.00396) benchmark - a large-scale corpus of naturally generated hallucinations, featuring detailed word-level annotations specifically designed for retrieval-augmented generation (RAG) scenarios.

Here, we check for the `hallucination` of AI responses i.e. 'Is the information provided in the response directly supported by the context given in the related passages?'

<br>
Get in touch with us if there's another use case you'd like to see a cookbook for!

support@atla-ai.com
