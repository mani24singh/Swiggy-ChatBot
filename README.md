# Swiggy-ChatBot
## **How Swiggy ChatBot Works using NLP**

### Natural Language Processing: 
- **Importing Libraries & Modules:** Import nltk and numpy libraries for the text preprocessing.\
import nltk\
import numpy as np
- **Tokenization:** Downloading 'punkt' model to tokenize message and importing 'word_tokenize' for word tokenization.
- **StopWords:** Loading the complete list of all the common stop-words that needs to be discarded.
- **Lemmatization:** Downloading all the lemmas present in English Language & WordNetLemmatizer for lemmetization.
- **Vectorization:** We can define our own function for stop-words removal, tokenization & lemmatization. It takes the corpus of words as an argument. You can learn more about it from: https://en.wikipedia.org/wiki/Tf-idf

### Intent classification:
- Loading the intents from 'intents.json' file. Download from here https://techwithtim.net/wp-content/uploads/2019/05/json-file.zip
- Reshaping the vectors for neural network.
- Defining the function to predict intent tag of a particular message.
- Defining the function to fetch the tag of the intent.
- Using all the functions which we have defined to classify intent and perform action accordingly are integrated together to develop our final chatBot.

### References: 
[Techlearn](https://www.techlearn.live/'link')
[techwithtim](https://www.techwithtim.net/tutorials/ai-chatbot/part-1/ 'link')

