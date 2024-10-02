# LLMs and Readability

This repository contains code and data to:

- Estimate readability of text excerpts in the [CLEAR corpus](https://link.springer.com/article/10.3758/s13428-022-01802-x) using GPT-4 Turbo and GPT-4o mini.  
- Calculate intrinsic dimensionality of embedding matrices for text excerpts using RoBERTa.
- Analyze results.


## Data

`raw` contains the raw `.csv` file with the original corpus.

`processed/readability_basic_gpt-4-1106-previous.csv` contains the judgments from GPT-4 Turbo and `readability_basic_gpt-4o-mini-2024-07-18.csv` contains the judgments from GPT-4o mini.

## Notebooks

See `Exploring CLEAR Dataset` for descriptive statistics and visualizations of the CLEAR corpus.

See `GPT and Readability` for the pipeline to actually create the readability estimates from GPT.
