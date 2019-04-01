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
