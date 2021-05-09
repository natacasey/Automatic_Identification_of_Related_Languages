![picture](https://github.com/natacasey/Automatic_Identification_of_Related_Languages-/blob/main/_assets/lang1.png)

## Project description and Data

Relying on the data from the [the multilingual Amazon reviews corpus](https://registry.opendata.aws/amazon-reviews-ml/) this project focuses  on creating a language detector that is capable of recognizing the realted languages of English, German, Spanish and French. Informative linguistic features of each of the related languages mentioned above, different text data preprocessing techniques, and such supervised models as Multinomial Naïve Bayes, Logistic Regression, Random Forest, Suppport Vector Machines, and a bidirectional LSTM are used in this project to create a pipeline capable of successfully identifying these languages even on short strings of both informal and formal text data from [European Parliament Proceedings Parallel Corpus](https://www.statmt.org/europarl/archives.html#v6).


## Documentation

All of the documentation can be found in the docs folder.

## Development

- Programming langauge - Pyhon, 3.7.2 
- OS - Windows 10 Home.


## Final classification model

Multinomial Naïve Bayes with the maximum features of 1,000,000 had the highest performance for long and short versions of formal and informal text samples. No problematic classes to predict were identified.


## Results of the final model

- 99.994% accuracy for the informal long strings of text data
- 100% accuracy for an 80-observation sample of short (3-word) infromal text data
- 100% for an 80-observation sample of long formal text data
- 98.75% for an 80-observation sample of short (3-word) formal text data

## Project challenges and limitations
- includes only 4 languages
- needs testing on more samples from different domains


## Consideration for the future:
The model can be improved by adding more langauges and testing it on more samples. 
