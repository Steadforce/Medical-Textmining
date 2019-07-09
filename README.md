# Medical-Textmining
This is a demonstration of text mining techniques in clinical data using pyspark in a Zeppelin notebook. Github cannot not render Zeppelin notebooks - to view this notebook, import it in your own Zeppelin server or take the URL of the raw file here at github and get a preview at [https://www.zepl.com/explore](https://www.zepl.com/explore).

This demo was implemented by [Jonathan Boidol](mailto:jonathan.boidol@steadforce.com) and [Stephan Schiffner](mailto:stephan.schiffner@steadforce.com) at [Steadforce GmbH](https://steadforce.com/).

## Data Source

We used data freely available (in XML format) at [https://clinicaltrials.gov/](https://clinicaltrials.gov/).

## NLP (and NER) Models

We use different pre-trained NLP models to analyze the data set, available for python using [langdetect](https://pypi.org/project/langdetect/), [spaCy](https://spacy.io/) and [medaCy](https://github.com/NLPatVCU/medaCy).
MedaCy models are particularly useful for the medical domain with their ability to detect medication usage, dosis, reason and side effects.

