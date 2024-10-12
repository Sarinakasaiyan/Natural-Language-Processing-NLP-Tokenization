#Text Tokenization with NLTK in Natural Language Processing

This project demonstrates how to use the NLTK (Natural Language Toolkit) module for text tokenization. Tokenization is a fundamental step in Natural Language Processing (NLP) that divides text into smaller, processable units.


[section 1]

This code uses the NLTK library to tokenize a given sentence into individual words. It downloads the necessary data and prints the tokens, including words and punctuation marks, from the input string.


<center><img width="452" alt="image" src="https://github.com/user-attachments/assets/f9374ee8-a30b-4b41-810e-bf791e367825"></center>



[section 2]

This code uses the NLTK library to tokenize a sentence into individual words. After downloading the necessary data, it prints the tokens, which include only words and punctuation marks from the input string, while special characters like `\n` are ignored.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/5326eda1-5eac-49bf-8a5a-e767247c347a">


[section 3]

This code uses the NLTK library to tokenize a text into separate sentences. After downloading the necessary data, it prints the sentences from the input string, and special characters like `\n` are recognized as separate tokens.


<img width="452" alt="image" src="https://github.com/user-attachments/assets/d00a67ab-04c5-4427-90c9-70f8e30464ff">


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


<img width="452" alt="image" src="https://github.com/user-attachments/assets/28166a6f-b226-400e-844d-8d9605acd4c4">


Regular Expression [How to find all the in the text?]

[^a-zA-Z]?[tT]he[^a-zA-Z]

Test String [https://www.regexpal.com]

<img width="452" alt="image" src="https://github.com/user-attachments/assets/887bca29-149d-4441-8ac8-ded184e374e2">

Regular Expression
[How to find all the in the text except for the first sentence. By not leaving a question mark]

[^a-zA-Z] [tT]he [^a-zA-Z]

Test String [https://www.regexpal.com]

<img width="452" alt="image" src="https://github.com/user-attachments/assets/94af2cd9-1717-4f8e-8c8b-91598d906fc5">


