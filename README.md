# Pig Latin Translator


#### By Meaghan Jones and Caleb Stokka

## Description

This webpage takes a word input and returns the pig latin translation of the word

## Specs
The program should ad "ay" to words that begin with a vowel.
* Input example: animal
* Output example: animalay <br>

For words that begin with a single consonant, the program should move the first consonant to the end of the word, then add "ay".
* Input example: cat
* Output example: atcay <br>

For words that begin with multiple consonants, the program should move the beginning consonants to the end of the word, then add "ay".
* Input example: train
* Output example: aintray <br>

For words that begin with a "y", the program should move the "y" to the end of the word, then add "ay".
* Input example: yellow
* Output example: ellowyay <br>

For words that begin with a "qu", the program should move the "qu" to the end of the word, then add "ay".
* Input example: quiet
* Output example: ietquay <br>

For words that begin with consonants followed by "qu", the program should move the consonants and "qu" to the end of the word, then add "ay".
* Input example: squirt
* Output example: irtsquay <br>

For blank strings, the program should return false.
* Input example: " "
* Output example: Please enter a word <br>

For numbers, the program should return false.
* Input example: 12
* Output example: Please enter a word <br>

For strings longer than a word, the program should return false
* Input example: "hello my name is"
* Output example: Please enter a word <br>
