# python-nlp
Jupyter notebooks from following the Tutorials from "[Natural Language Text Processing with Python][book]" by Jonathan Mugan

The following libraries are used:
* `nltk` (v3.6.2): https://www.nltk.org/
* `spaCy` (v3.1.1): https://spacy.io/usage
* `gensim` (v4.0.1) : https://radimrehurek.com/gensim/
* `pyLDAvis` (v3.3.1): https://pyldavis.readthedocs.io/en/latest/index.html
* `pyspotlight` (v0.7.2): https://github.com/aolieman/pyspotlight
* `rdflib` (v6.0.0): https://rdflib.readthedocs.io/en/stable/
* `scikit-learn` (v0.24.2): https://scikit-learn.org/stable/index.html
* `textblob` (v0.15.3): https://textblob.readthedocs.io/en/dev/
* `vaderSentiment` (v3.3.2): https://github.com/cjhutto/vaderSentiment

## Getting started

Install dependencies using the following command:

```bash
pip install -r requirements.txt
```

### `spaCy` library

The following command needs to be run to install the English dependencies for `spaCy`

```bash
python -m spacy download en_core_web_sm
```

[book]: https://www.oreilly.com/library/view/natural-language-text/9781491976487/
