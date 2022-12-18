# wordemb-gender-bias
Use word embeddings to measure gender stereotypes in different countries / languages. 

We leverage this code: https://wefe.readthedocs.io/en/latest/user_guide/measurement_user_guide.html to score gender biais in fasttext word embedding from different languages. We use `WEFE` (biais evaluation), `gensim` (handles word vectors) and `fasttext` pre-trained models. 

## Download the English model 

Here: https://fasttext.cc/docs/en/crawl-vectors.html

## Download the code

Copy paste the notebook `score_bias_in_word_vectors.ipynb`

## Build environment

```
conda create --name="wordemb_gender_bias" python=3.7
conda activate wordemb_gender_bias
```

## Install requirements

Go to the root of the folder (where the file `score_bias_in_word_vectors.ipynb` is)
and run the follwing command (make sure to have installed the environment first)

```
pip install -r requirements.txt
```

## Run the notebook

Run each cell of the notebook `score_bias_in_word_vectors.ipynb`. 
