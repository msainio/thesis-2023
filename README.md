This repository contains NLI data and code for my Bachelor's thesis.

The 'MNLI-NOUN-int.tsv' data was created by modifying the 'CorruptTest/MNLI-NOUN.tsv' data, which was copied from
'https://github.com/Helsinki-NLP/nli-data-sanity-check'. The data was modified by changing the alphabetical gold labels
to numerical ones, so that they may be used to evaluate a fine-tuned transformers model. The 'MNLI-NOUN-int-subset.tsv' data
is a randomly sampled 50-pair subset of 'MNLI-NOUN-int.tsv'.

The training and evaluation scripts in 'experiment.ipynb' are based on those by Aarne Talman ('https://github.com/aarnetalman/Notebooks/blob/main/natural-language-inference-with-pytorch-and-transformers.ipynb').
