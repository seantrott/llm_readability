# LLMs and Readability

This repository contains code and data to reproduce the analyses described in this newsletter post.

In summary, I used GPT-4 Turbo to estimate the readability of text excerpts in the [CLEAR corpus](https://link.springer.com/article/10.3758/s13428-022-01802-x), and then asked how precise these estimates were.


## Data

`CLEAR-Corpus` contains the raw `.csv` file with the original corpus.

`processed/readability_basic_gpt-4-1106-previous.csv` contains the judgments from GPT-4 Turbo.

## Notebooks

See `Exploring CLEAR Dataset` for descriptive statistics and visualizations of the CLEAR corpus.

See `GPT and Readability` for the pipeline to actually create the readability estimates, as well as analyze and compare them to the human gold standard.
