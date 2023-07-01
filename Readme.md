## EMO AI 2023

we use sbert bi encoder and RoBERTa to implement model that learns from the context of dialogues & predicts emotion of all the users better.

### model

single sentence model:   <a target="_blank" id="bt" href = "https://colab.research.google.com/github/Kelvinthedrugger/-AI-/blob/main/emo_nbs/CODE_EXAMPLE_TO_PUSH/EMO_AI_context_model/Gradual_unfreeze_example.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

emo ai:   <a target="_blank" id="bt" href = "https://colab.research.google.com/github/Kelvinthedrugger/EmoAI2023/blob/master/Emo_ai_2023_on_github.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>


### training result

<img src="https://github.com/Kelvinthedrugger/EmoAI2023/blob/master/assets/single_vs_roberta_vs_with_pseudo.png" width="300" height="250">

left: model without context analysis

middle: with context analysis, without training on pseudo labelled data

right: with context analysis, training on pseudo labelled data

