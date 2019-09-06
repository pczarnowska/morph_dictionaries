# Morphologically Complete Dictionaries

The morphologically complete dictionaries contain most of the inflectional paradigm of every word they hold. They consist of many rare forms, some of which are out-of-vocabulary for large-scale word embeddings and can be used for evaluating open-vocabulary BLI. 

In every dictionary, each source–target pair is followed by their corresponding lemmata and a shared morphosyntactic tag. 

This repository holds dictionaries between 5 languages from the Slavic family:

* Polish
* Czech
* Russian 
* Slovak
* Ukrainian

and 5 Romance languages:

* French
* Spanish
* Italian
* Portuguese
* Catalan

Each dictionary is split into train, development and test splits so that every split has its own, independent set of source lemmata; the train splits contain 60% of the lemmata, while the development and test dictionaries each have 20% of the lemmata.
