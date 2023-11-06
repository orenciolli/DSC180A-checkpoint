# Overview

Code for the baseline models implemented for three tasks across two datasets: NLI on the SNLI dataset, poltical affiliation classification on the LIAR dataset, and veracity prediction on the LIAR dataset. I'll revisit the political affiliation task by adding complexity to my baseline model (and possibly using a different dataset). I'll likely abandon the text-only approach to veracity prediction in favor of an entailment-based approach (hence the experimentation with SNLI), as this seems to be more robust and accurate.

## Data
- SNLI: Available through the [Stanford NLP](https://nlp.stanford.edu/projects/snli/) website. The archive can be downloaded through the "download" link and unzipped in the same directory as my SNLI_notebook.ipynb to facilitate its execution.
- LIAR: Available at [HuggingFace](https://huggingface.co/datasets/liar), among other sources. This dataset can be downloaded, and all files can be placed in the same directory as my clean_liar_bias_classification.ipynb and liar_party_classification.ipynb files.

## Packages
- All code is implemented in either PyTorch or TensorFlow/Keras. Standard data science/ML packages (Pandas, NumPy, and sk-Learn) are also employed.
- Code is implemented in Jupyter Notebooks, which can be run sequentially to reproduce the results.
- Pretrained models are provided by HuggingFace through the [transformers package](https://huggingface.co/docs/transformers/index)
