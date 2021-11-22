# Spelling-Correction-using-Tokenization-and-LevenshteinDistancezation-and-La
The spelling corrector follows every sentence and tokenizes each word of it based on whitespace. Special characters like punctuation and newlines are then re- tokenized and separated from the word start and end of the word to assemble an array of words. Additionally, all capitalizations are removed from the word and the indices of the capitalizations are stored. The list of clean words are passed through a word list, one at a time to check for spellings from a list of words. The word with the least Levenshtein distance from the misspelt word is treated as the one with correct spelling. In the case of a tie, the most frequently used word is treated as the true spelling. This method is repeated for the entire corrupted input string of Jane Austen’s Sense and Sensibility. Lastly the array of corrected words is then put together again using a join function while adding the special characters back and capitalizing the characters. An sample file, called bug_free.txt is the file after error check.
