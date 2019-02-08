# NLP-Assigment1
Question 1:
Download a library that supports Porter’s stemmer and use it to stem the words in file “content.txt”. The results are to be stored in a new file called “stemmed-content.txt”. Then, create another file “counts-statisitcs.txt” that stores the frequency of each word in stemmed-content.txt, each <word, freq> pair in a separate line. The source code + the three files should be placed in a folder called “Q1”.


Question 2:
Write an application that uses regular expressions to search for the following items in file (content.txt):
1.	All words starting with capital letters and have a length of at least 4 characters. The words are to be stored in file (p1.txt), each word in a separate line.
2.	All words where either the last letter or the preceding one is ‘e’, provided that all other letters are consonants (non-vowels). The words are to be stored in file (p2.txt), each word in a separate line.
3.	Abbreviations that consists of uppercase letters and zero or more dots such that 
a.	The abbreviation should start with a letter
b.	No consecutive dots are allowed
The abbreviations are to be stored in file (p3.txt), each word in a separate line.
The source code + the three files (content.txt, p1.txt, p2.txt, p3.txt) should be placed in a folder called 

Q3
In Java, use “Pattern” and “Matcher” classes to build a regular expression using which one can extract phrases that are used in the beginning of a sentence, followed by a comma, and contain at most 4 words. 
For example: 

if the input is:
“In this blog, I will focus on the challenges pertaining to model evaluation I came across while implementing a machine log analytics classification algorithm. Specifically, I will demonstrate the meaning of model evaluation metrics”
Then, the output will be: 
In this blog
Specifically


(The input file is “content.txt” and the output will be printed on screen, each matched token in a separate line. The .java source code and “content.txt” file should be stored in folder Q3)
