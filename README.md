<p align="center">
  <picture>
    <source 
      srcset="https://atla-ai.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Ff08e6e70-73af-4363-9621-90e906b92ebc%2F1bfb4316-1ce6-40a0-800c-253739cfcdeb%2Fatla_white3x.svg?table=block&id=17c309d1-7745-80f9-8f60-e755409acd8d&spaceId=f08e6e70-73af-4363-9621-90e906b92ebc&userId=&cache=v2"
      media="(prefers-color-scheme: dark)"
      width="200"
    />
    <source 
      srcset="https://atla-ai.notion.site/image/attachment%3A230448e8-921f-45df-b2af-a3158b6c04cd%3Aatla_black2x.png?table=block&id=188309d1-7745-805c-87e4-c39ca54d598d&spaceId=f08e6e70-73af-4363-9621-90e906b92ebc&width=2000&userId=&cache=v2"
      media="(prefers-color-scheme: light)"
      width="200"
    />
    <img 
      src="https://atla-ai.notion.site/image/attachment%3A230448e8-921f-45df-b2af-a3158b6c04cd%3Aatla_black2x.png?table=block&id=188309d1-7745-805c-87e4-c39ca54d598d&spaceId=f08e6e70-73af-4363-9621-90e906b92ebc&width=2000&userId=&cache=v2"
      width="200"
    />
  </picture>
</p>
<p align="center">🧑‍⚖️ <a href="https://www.atla-ai.com/blog">Atla Blog</a> | 📄 <a href="placeholder">Technical report</a> | 💻 <a href="https://github.com/atla-ai">GitHub</a></p>

## [Selene Mini]((https://huggingface.co/AtlaAI/Selene-1-Mini-Llama-3.1-8B))

Selene Mini is a **state-of-the-art small language model-as-a-judge (SLMJ)**. Selene Mini achieves comparable performance to models 10x its size, **outperforming GPT-4o on [RewardBench](https://huggingface.co/spaces/allenai/reward-bench), [EvalBiasBench](https://arxiv.org/abs/2407.06551), and [AutoJ](https://arxiv.org/html/2310.05470v2)**.

Post-trained from Llama-3.1-8B across a wide range of evaluation tasks and scoring criteria, Selene Mini **outperforms prior small evaluation models overall across 11 benchmarks covering three different types of tasks:**  

- Absolute scoring, e.g. "Evaluate the harmlessness of this response on a scale of 1-5"
- Classification, e.g. "Does this response address the user query? Answer Yes or No."
- Pairwise preference. e.g. "Which of the following responses is more logically consistent - A or B?"

It is also the **#1 8B generative model on [RewardBench](https://huggingface.co/spaces/allenai/reward-bench)**.

## Resources

This repo features prompt templates used during training and hands-on examples for using Selene Mini.

