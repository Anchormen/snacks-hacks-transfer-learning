# Setup

## Install python (anaconda)
1. If you don't have it, install a python distribution with pip. We're going to use anaconda. Install from here:  https://www.anaconda.com/distribution/

## Create a virtual environment and install requirements
1. Create a new virtual environment and make sure pip is in there, for instance: `conda create --name bert pip`

1. Activate it `conda activate bert`

1. Clone the git repository for this snacks and hacks: `git clone https://github.com/Anchormen/snacks-hacks-transfer-learning.git`

1. Change working directory to the folder where the repo has been cloned (e.g., `cd snacks-hacks-transfer-learning`), and install the requirements: `pip install -r requirements.txt`

## Get the notebook

1. Clone the bert repository from google research (navigate out of the snacks hacks repository first, e.g. `cd ..`): `git clone https://github.com/google-research/bert.git`

1. Navigate to the bert repo `cd bert`

1. Open the notebook using `jupyter notebook` and find `predicting_movie_reviews_with_bert_on_tf_hub.ipynb` in the screen that opens up in your web browser.

# Snacks & Hacks To Do

1. **Make the notebook work.** Training on your laptop's CPU will take a long time with the current settings, so make sure to set the number of epochs to 1 and the number of random samples to use for training to 1000. Training should then take ~15 minutes.  (TOTALLY OPTIONAL: If you want to train faster with TPU's, you can create a google cloud platform account which comes with $300 free credit, and then run this notebook in Google Colab: https://colab.research.google.com/github/tensorflow/tpu/blob/master/tools/colab/bert_finetuning_with_cloud_tpus.ipynb. However, this is totally optional, and can be skipped.)

1. **Adapt the notebook to fine-tune Bert with new data to apply it to a new interesting NLP problem.** Find datasets here: https://github.com/niderhoff/nlp-datasets or https://www.figure-eight.com/data-for-everyone/.

Have fun!

# Links

- Papers
  - BERT paper: https://arxiv.org/abs/1810.04805
  - Transformers paper (Attention is all you need): https://arxiv.org/abs/1706.03762
- Useful blogs:
  - Illustrated Bert: http://jalammar.github.io/illustrated-bert/
  - Illustrated Transformers: https://jalammar.github.io/illustrated-transformer/
