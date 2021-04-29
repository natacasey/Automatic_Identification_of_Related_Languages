![picture](https://github.com/natacasey/Automatic_Identification_of_Related_Languages-/blob/main/_assets/lang.png)

## Project description and Data

Relying on the data from the [the multilingual Amazon reviews corpus](https://registry.opendata.aws/amazon-reviews-ml/) this project focuses  on creating a language detector that is capable of recognize the realted languages of English, German, Spanish and French. Informative linguistic features of each of the related languages mentioned above, different text data preprocessing techniques, and such supervised models as Multinomial Naïve Bayes, Logistic Regression, Random Forest, Suppport Vector Machines, and a bidirectional LSTM are used in this project to create a pipeline capable of successfully identifying these languages even on short strings of both informal and formal text. 


## Documentation

All of the documentation can be found in the docs folder.

## Development

- Programming langauge - Pyhon, 3.7.2 
- OS - Windows 10 Home.


## Final classification model

Multinomial Naïve Bayes with the maximum features of 1,000,000 had the highest performance for long and short versions of formal and informal text samles.  


## Results of the final model



## Project challenges and limitations
- includes only 4 languages
- not enough support for multilingual embeddings in text that has more than 1 language


## Consideration for the future:
The model can be improved by adding more langauges
