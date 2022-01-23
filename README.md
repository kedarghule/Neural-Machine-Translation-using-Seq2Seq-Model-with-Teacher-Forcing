# Neural Machine Translation using Seq2Seq Model with Teacher Forcing

The dataset for this project is found at this [link](http://storage.googleapis.com/download.tensorflow.org/data/spa-eng.zip).

### Data Cleaning and Preprocessing

In natural language processing, text preprocessing is the first step in the process of building a model. We perform the following text preprocessing techniques- 

- **Lower casing**: Converting a word to lower case (NLP -> nlp). Words like Book and book mean the same but when not converted to the lower case those two are represented as two different words in the vector space model (resulting in more dimensions).
- **Stop words removal**: Stop words are very commonly used words (a, an, the, etc.) in the documents. These words do not really signify any importance as they do not help in distinguishing two documents.
- **Punctuation Removal**: Punctuations are commonly used in sentences and therefore should be removed as they do not have much importance.
- **Lemmatization**: Lemmatization reduces the words to a word existing in the language.

### Natural Language Processing
