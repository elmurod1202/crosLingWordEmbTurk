# Cross Lingual Word Embeddings for Turkic Languages

This repository consists of language resources reported on a paper wih the same title at LREC2020 paper by Elmurod Kuriyozov, Yerai Doval and Carlos Gomez-Rodriguez (link to the paper will be announced soon).

## Bilingual dictionaries

### 1. From available sources
There are dictionaries obtained from existing resources for Turkish-English and Uzbek-English (Kazakh-English reported at the paper cannot be shared due to licence issues).

Turkish-English dictionary was obtained from [MUSE](https://github.com/facebookresearch/MUSE)
Uzbek-English dictionary was obtained from [The Uzbek Glossary](http://www.uzbek-glossary.com/)
Kazakh-English dictionary file cannot be shared diractly, but can be obtained from [The Leneshmid Dictionary](http://kazakh-glossary.com/table1list.php)

### 2. Dictionaries obtained using Google Translate
There are dictionaries from five Turkic languages: Turkish, Uzbek, Azeri, Kazakh and Kyrgyz to English using Google Translate API.
Sizes (in words): 
Turkish - English: 9350
Uzbek - English: 7958
Azeri - English: 7422
Kazakh - English: 8454
Kyrgyz - English: 7974


## Word-embeddings
Pre-trained word embeddings for these five Turkic languages are available already, one of them we used for our experiment is [FastText](https://fasttext.cc/docs/en/crawl-vectors.html)

Apart from that, we trained our own word embeddings with skip-gram model of FastText using Large Corpora of Turkic Languages[Baisa et al. 2012](https://www.muni.cz/en/research/publications/982494)

All pre-trained word embeddings can be downloaded from links below.

Turkish FastText skip-gram 300d word-embeddings - [Download] (https://zenodo.org/record/3666697/files/tr.sg.300.vec.tar.gz?download=1)
Uzbek FastText skip-gram 300d word-embeddings - [Download] (https://zenodo.org/record/3666697/files/uz.sg.300.vec.tar.gz?download=1)
Azeri FastText skip-gram 300d word-embeddings - [Download] (https://zenodo.org/record/3666697/files/az.sg.300.vec.tar.gz?download=1)
Kazakh FastText skip-gram 300d word-embeddings - [Download] (https://zenodo.org/record/3666697/files/kk.sg.300.vec.tar.gz?download=1)
Kyrgyz FastText skip-gram 300d word-embeddings - [Download] (https://zenodo.org/record/3666697/files/ky.sg.300.vec.tar.gz?download=1)


