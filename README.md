# Checkpoint-Algorithms-and-its-elements

 The problem to be solved is to create an algorithm which can read a senrtence character by character
 to determine:

The length of the sentence (the number of characters).
The number of words in the sentence (assuming that the words are separated by a single space).
The number of vowels in the sentence.

To achieve that we would go through the following steps:

- create variables for the elements we are gonna be counting which includes the character counter, the word counter. vowel counter amd even the space counter
- create variable for the sentence
- Let the algorithm begin by reading the sentence
- Now we create a while loop that checks if the index(i) is less than the sentence.length
- if true it runs a code that then checks if the the index(i) is equal top a space " "
- if true it adds +1 to the space counter variable which was zero initially, this would help us be able to count the
amount of spaces in the sentence
- if the index(i) isn't equal to a space " " then its adds to the character counter variable thereby allowing us to count
  how many characters that are in the sentence
- Now for us to check for the amount of vowels in the sentence we can run a SWITCH loop that checks all the characters of the vowel to see
if the index(i) is a vowel, if true its adds a +1 to our vowel counter
- At the end of the while loop, its adds a +1 to the index of the sentence so it could run the whole procedure on the new index(i)
- Now in order for us to get the amount of words in  the sentence we get the amount of spaces in the space counter the add a +1 on it to
  know the amount of words in the sentence

  once we are done now we can now WRITE the character counter, word counter and vowel counter out for the algorithm to output
