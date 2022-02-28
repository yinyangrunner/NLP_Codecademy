### Which facet of NLP is demonstrated in the code?

``` py 
{
 def is_plagiarized(text1, text2):
   n = 7
   if edit_distance(text1.lower(), text2.lower()) > ((len(text1) + len(text2)) / n):
     return False
   return True 
   }
```

*Answer: **Text Similarity** (Edit distance — or Levenshtein distance — is a facet of text similarity.)*

### Which of the following scenarios would NOT necessarily require a language model?

*Answer: **Building a spellcheck function** (Although language models like NLM could improve spellcheck, spellcheck could rely on entirely distance functions to gauge text similarity.)*

### Which language model does most_common_language_in_looking_glass use?

``` py 
{
print(most_common_language_in_looking_glass)
 
# prints the following to console:
[(('of', 'the'), 101), (('said', 'the'), 98), (('in', 'a'), 97), (('in', 'the'), 90), (('as', 'she'), 82), (('you', 'know'), 72), (('a', 'little'), 68), (('the', 'queen'), 67), (('said', 'alice'), 67), (('to', 'the'), 66)]

   }
```
*Answer: **n-gram model with n set to 2** (This is also known as a bigram model.)*

### Which of the following would not be a part of text preprocessing?
*Answer: **n-gram model with n set to 2** (This is also known as a bigram model.)*

### NLTK is a __. 
*Answer: **Python library used for NLP** (The Natural Language Toolkit (NLTK) is a common NLP Python library that handles some preprocessing, parsing, language modeling, and text similarity tasks.)*

### The code below illustrates *which* challenge within NLP?

``` py 
{
review = "it was aight"
 
classify_review(review)
 
# returns the following:
"This review is negative."

   }
```

*Answer: **Language varies by person, by dialect, and by many sociolinguistic factors.** (Aight is a slang term (for “alright”) which a classifier may not have been trained on.)*

### Take a look at the topics returned by your LDA topic model. Which of the following tasks would help you get a better sense of your texts’ topics?

``` 

Topics identified in text:
Topic #1: say put you there
Topic #2: there say place man
Topic #3: put man say when
Topic #4: had man one place
Topic #5: know say came see
Topic #6: came say place man
Topic #7: say could one there
Topic #8: place come say one
Topic #9: say man when case
Topic #10: say point man one

```

*Answer: **Either filtering the language model for stop words before performing LDA or using a tf-idf model before performing LDA.** *

### Which of the following is NOT an application of natural language processing?
*Answer: **An alarm that rings at 5 pm every day.** (This would not require any NLP.)*

### What is parsing in NLP?
*Answer: **Breaking up text based on grammar.** 

### Your Dominican friend is a native Caribbean Spanish speaker and uses a Spanish language virtual assistant that often does not understand him. Why could this be happening?
*Answer: **The virtual assistant might be trained without accounting for Caribbean Spanish dialects.**  (The training data may be entirely from Spain or from a non-Caribbean part of Latin America.)*

