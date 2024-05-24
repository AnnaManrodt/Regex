# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

(^\d{5}$)|(^\d{5}-\d{4}$)

This regular express is for zip code valdtation. (^\d{5}$) this is the frist grouping the code will look at. Each set of paratheiis indeicate a new grouping which are sperated by this | symbol.
    ^ this symbol indeicates the we are starting a new line.
    \d matches the digit so its a character from 0-9
    {5} repeates \d opperation 5 times total

(^\d{5}-\d{4}$) this the second part if the frist part fails, this is another alterintive the will validate the zip code.
        ^ this symbol indeicates the we are starting a new line.
        \d matches the digit so its a character from 0-9
        {5} repeates \d opperation 5 times total
        - matches the the - character
        \d matches the digit so its a character from 0-9
        {4} repeates \d 4 times total 
        and finally $ lets the code know its the end of the line

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
