#### 1. What is the name of the object used to tokenize sentences?
##### Ans: Tokenizer
#### 2. What is the name of the method used to tokenize a list of sentences?
##### Ans: fit_on_texts(sentences)
#### 3. Once you have the corpus tokenized, what’s the method used to encode a list of sentences to use those tokens?
##### Ans: texts_to_sequences(sentences)
#### 4. When initializing the tokenizer, how to you specify a token to use for unknown words?
##### Ans: oov_token=<Token>
#### 5. If you don’t use a token for out of vocabulary words, what happens at encoding?
##### Ans: The word isn’t encoded, and is skipped in the sequence
#### 6. If you have a number of sequences of different lengths, how do you ensure that they are understood when fed into a neural network?
##### Ans: Use the pad_sequences object from the tensorflow.keras.preprocessing.sequence namespace
#### 7. If you have a number of sequences of different length, and call pad_sequences on them, what’s the default result?
##### Ans: They’ll get padded to the length of the longest sequence by adding zeros to the beginning of shorter ones
#### 8. When padding sequences, if you want the padding to be at the end of the sequence, how do you do it?
##### Ans: Pass padding=’post’ to pad_sequences when initializing it