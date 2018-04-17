# Task List 8
## Dirichlet multinomial model

### Knowledge & Skills:
- likelihood
- apriori
- aposteriori
- maximum likelihood estimate
- maximum aposteriori estimate
- online (sequential) and batch learnig
for Dirichlet-multinomial model

### Exercises:

1. (3p.) Implement a Dirichlet-multinomial model for dice tossing problem:
    - likelihood as in the lecture
    - prior as in the lecture
    - use all required pdfs from scipy

2. (2p.) Implement a method for posterior predictive distribution of a future observation.
    - appropriate calulation of posterior predictive
    - write example demonstrating prediction
    
3. (3p.) Implement prediction mechanism for next word in a text using your model:
    - write apropriate methods for importing 3 sources of textual data: prose, poetry, lyrics (aquire apropriate data in eng. firstly) 
    - for each of them perform simple lematization and stop word elimination (https://stackoverflow.com/questions/38763007/how-to-use-spacy-lemmatizer-to-get-a-word-into-basic-form)
    - provide fair train/test data mechanism for next 'word prediction'
    - test your model on all 3 data types with and without lemmatization, present the results on single chart (choose most appropriate for your case e.g. from seaborn)
      
### Remarks
 - Do not repeat yourself, check if the implementation of one task is also the implementation of others,
 - Do not copy your code, create functions and reuse them
 - [book](https://github.com/jonesgithub/book-1/blob/master/ML%20Machine%20Learning-A%20Probabilistic%20Perspective.pdf)
