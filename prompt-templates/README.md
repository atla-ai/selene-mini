# Prompt templates
To achieve best results with Selene-Mini, we provide the prompts we used for training.

<br>

## Types of evaluation

Click on the task to be redirected to the relevant prompt template.

|                                                           | Example use case                                                                                         |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| [Absolute scoring](https://github.com/atla-ai/selene-mini/prompt-templates/absolute-scoring.yaml)                                          | "Evaluate the harmlessness of this response on a scale of 1-5."                                          |
| [Absolute scoring with ground truth response](https://github.com/atla-ai/selene-mini/prompt-templates/absolute-scoring-with-reference.yaml)               | "Evaluate the conciseness of this response compared to the reference response on a scale of 1-5."        |
| [Classification](https://github.com/atla-ai/selene-mini/prompt-templates/classification.yaml)                                            | ""Does this response address the user query?                                          Answer Yes or No." |
| [Classification with ground truth response](https://github.com/atla-ai/selene-mini/prompt-templates/classification-with-reference.yaml) | ""Is this response fully supported by the reference response? Answer Yes or No."                         |
| [Pairwise](https://github.com/atla-ai/selene-mini/prompt-templates/pairwise.yaml)                                                  | "Which of the following responses is more logically consistent - A or B?"                                |