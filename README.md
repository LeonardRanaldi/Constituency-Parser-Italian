# Constituency-Parser-Italian


## Getting Started

### Prerequisites

- Python 3
- nltk, sklear, PYEVALB packages.

### Installation

```
pip install nltk
pip install scikit-learn
pip install PYEVALB
```

## Arguments

```--data_train```    : - File containing training data 

```--train_size```    : - Ratio of the data to train on, used only with train_eval option (default=0.9)

```--n_words_formal```: - Number of closest words w.r.t formal similarity (default=2)

```--n_words```       : - Number of closest words w.r.t embedding similarity (default=20)

```--swap```          : - Use Damerau-Levenstein distance when true and Levenstein distance otherwise.

```--lambd```         : - Float in \[0, 1\], the interpolation parameter between bigram and unigram models (default=0.8)

## Usage

The details are explained in the constituency_parser.ipynb [https://github.com/LeonardRanaldi/Constituency-Parser-Italian/blob/main/constituency_parser.ipynb] notebook.








