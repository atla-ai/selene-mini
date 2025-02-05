# Absolute Scoring (Tutorial)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/atla-ai/selene-mini/blob/main/cookbooks/HF_Quickstart_Absolute_Scoring.ipynb)

This example gets you started running evals with absolute scores, and does so on a sample set from the public benchmark [FLASK](https://arxiv.org/pdf/2307.10928) dataset - a collection of **1,740 human-annotated samples from 120 NLP datasets**. Evaluators assign scores ranging from 1 to 5 for each annotated skill based on the reference (ground-truth) answer and skill-specific scoring rubrics.

Here, we evaluate the `completeness` of AI responses i.e. 'Does the response provide a sufficient explanation?'

# Hallucination Scoring (Tutorial)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/atla-ai/selene-mini/blob/main/cookbooks/HF_Quickstart_Hallucination.ipynb)

This example gets you started detecting hallucinations, and runs over a sample set from the public benchmark [RAGTruth](https://arxiv.org/abs/2401.00396) benchmark - a large-scale corpus of naturally generated hallucinations, featuring detailed word-level annotations specifically designed for retrieval-augmented generation (RAG) scenarios.

Here, we check for the `hallucination` of AI responses i.e. 'Is the information provided in the response directly supported by the context given in the related passages?'

# Using Selene Mini with DeepEval (Tutorial)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/atla-ai/selene-mini/blob/main/cookbooks/DeepEval_Quickstart.ipynb)

This example gets you started running evaluations with DeepEval’s plug-and-play metrics / prompts using Selene Mini. We load our model using HF Transformers and mock the evaluation of a RAG QA Chatbot, assessing it on three metrics: **Context Relevance, Groundedness, and Answer Relevance.**

These evaluations help detect hallucinations in LLM responses by ensuring that:

1. **Context is relevant.**
2. **Responses are grounded.**
3. **Answers align with user queries.**

# Contact
Get in touch with us if there's another use case you'd like to see a cookbook for!

<p align="left">
  <a href="https://x.com/Atla_AI"><img src="https://img.shields.io/badge/Atla_AI-000?color=00bd83&style=plastic&logo=twitter&logoColor=white&label=X"></a>
  <a href="https://discord.com/invite/qFCMgkGwUK"><img src="https://img.shields.io/discord/1280604142536232972?color=00bd83&style=plastic&label=Discord&logo=discord&logoColor=white"></a>
  <a href="https://www.linkedin.com/company/atla-ai/"><img src="https://img.shields.io/badge/LinkedIn-Atla_AI-00bd83?style=plastic"></a>
<br></br>