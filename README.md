#Text Tokenization with NLTK in Natural Language Processing

<img width="1440" alt="Screenshot 1403-07-21 at 17 13 41" src="https://github.com/user-attachments/assets/0df33a09-2fc7-4681-8d04-4ccd0df6e007">



This project demonstrates how to use the NLTK (Natural Language Toolkit) module for text tokenization. Tokenization is a fundamental step in Natural Language Processing (NLP) that divides text into smaller, processable units.


[section 1]

This code uses the NLTK library to tokenize a given sentence into individual words. It downloads the necessary data and prints the tokens, including words and punctuation marks, from the input string.

[section 2]

This code uses the NLTK library to tokenize a sentence into individual words. After downloading the necessary data, it prints the tokens, which include only words and punctuation marks from the input string, while special characters like `\n` are ignored.

[section 3]

This code uses the NLTK library to tokenize a text into separate sentences. After downloading the necessary data, it prints the sentences from the input string, and special characters like `\n` are recognized as separate tokens.

[section 4]

This code uses the WordNet lemmatizer from the NLTK library to convert words to their base forms.

 Explanation:
 
- Importing Libraries : The NLTK and WordNetLemmatizer modules are imported.
- Creating an Instance : An instance of the WordNetLemmatizer is created.
- Lemmatization:
  - 'dogs' is reduced to 'dog'
  - 'pianos' is converted to 'piano'
  - 'python' remains unchanged
  - 'cheaper' is lemmatized to 'cheap' (pos="a")
  - 'better' remains 'better' (pos="n")
  - 'playing' is reduced to 'play' (pos='v')

 Summary:
The code demonstrates how to use the WordNet lemmatizer to reduce words to their base forms while considering parts of speech.
