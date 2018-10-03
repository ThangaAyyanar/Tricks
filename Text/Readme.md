
#### To Search a word in dictionary

below code find word start with "wor" followed by one word ( each . represent one character ) 

^ -> mark start of the word
$ -> mark end of the word

```
grep --ignore-case "^wor.$" /usr/share/dict/words
```
