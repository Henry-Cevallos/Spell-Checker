# Spell Checker

Author: Henry Cevallos

In this Repository there contains 3 different implementations of Hash Tables.

The first is `linear probing`.

The second is `quadratic probing`.

The third is with `double hash function`.

We will use wordsEn.txt which containswords of the english dictionary and place 
it into the most efficent hash table, the double hash function table. We can then 
check any text file text file passed for any errors by seeing if each word is in 
the dictionary, if not then it is a misspelled word and the program will suggest 
corrections for every word misspelled.

## Steps To Run
```sh
g++ spellChecker -o spell_check.cc -std=c++17

./spellChecker wordsEn.txt <filename>
```
*<filename> should be the txt file you want to spell check.
