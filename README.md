# Google-python-class
Practice programs that I attempted from the google python class

string1.py
----------------------

#A. donuts
Given an int count of a number of donuts, return a string
of the form 'Number of donuts: <count>', where <count> is the number
passed in. However, if the count is 10 or more, then use the word 'many'
instead of the actual count.
So donuts(5) returns 'Number of donuts: 5'
and donuts(23) returns 'Number of donuts: many'

# B. both_ends
Given a string s, return a string made of the first 2
and the last 2 chars of the original string,so 'spring' yields 'spng'. 
However, if the string lengthis less than 2, return instead the empty string.

# C. fix_start
Given a string s, return a string
where all occurences of its first char have
been changed to '*', except do not change
the first char itself.
e.g. 'babble' yields 'ba**le'
Assume that the string is length 1 or more.
Hint: s.replace(stra, strb) returns a version of string s
where all instances of stra have been replaced by strb.

# D. MixUp
Given strings a and b, return a single string with a and b separated
by a space '<a> <b>', except swap the first 2 chars of each string.
e.g.
   'mix', pod' -> 'pox mid'
   'dog', 'dinner' -> 'dig donner'
Assume a and b are length 2 or more.

---------------------------------------

#wordcount.py

1. For the --count flag, implement a print_words(filename) function that counts
how often each word appears in the text and prints:
word1 count1
word2 count2
...

Print the above list in order sorted by word (python will sort punctuation to
come before letters -- that's fine). Store all the words as lowercase,
so 'The' and 'the' count as the same word.

2. For the --topcount flag, implement a print_top(filename) which is similar
to print_words() but which prints just the top 20 most common words sorted
so the most common word is first, then the next most common, and so on.

#Note:
For the wordcount.py program, I've attached a companion txt file to work with it (small.txt). Please feel free to edit the small.txt file to your liking. Also, proper usage to invoke the command from terminal would be:

./wordcount.py {--count | --topcount} file ,for ex: ./wordcount.py --count small.txt

#list1.py and list2.py
These are another set of exercises by Google which I manged to solve as part of the intro. They were fun!

Again, Thank you to Google for getting those awesome Pyhton videos a copuple of years back. 



