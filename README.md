# HACKATHON_DARPG
### This is the Repository for code of the solution to problem statement 1
Approach 1:
Involves the use of Google word2vec model to find similarity scores between the `greivance text` and the `descrition string` of the organisation. The one with maximum score is the final destination of that greivance. The word2vec dictionary we've used is from Kaggle. The link to the dictionary is `https://www.kaggle.com/datasets/leadbest/googlenewsvectorsnegative300`. It can be downloaded and must be included while running the notebook.

Approach 2:
Involves use of LLM `ai4bharat/indic-bert` pretrained on 12 major Indian languages, which is fintuned on a smaller chunk of the given data, to generate inferences. Perfrmed well after a basic training of a much smaller chunk of the original dataset.
