# Regex Tutorial
As we move further along the bootcamp we are now learning computer science, in this project i demostrate how to use regex and i will be explaining a regular expression.

## Summary

In this tutorial I will be breaking down the following regular expression:
```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

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
### Pattern
```
^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$
```
### Modifiers
My expression doesnt have modifiers , if it did it will be after the / at the end of the pattern. For example Some modifiers include g which means global.
### Anchors
^ means it starts at the beggining of the string and $ means it ends the string.
### Quantifiers
\+ means the component has 1 or more occurrences. {2,6} It has to happen between 2 or 6 times.
### OR Operator
We dont have any. If it did it will look like this |
### Character Classes
Character classes is a set of characters, for example, alphabets, numbers, whitespaces. 
```
[a-z0-9_\.-]+
```
### Flags
A flag is an optional parameter to a regex that modifies its behavior of searching. We dont have any (g,m,i). If it did it will look like this /aBc/i
### Grouping and Capturing
A group is a part of a regex pattern enclosed in parentheses () and Capturing groups are a way to treat multiple characters as a single unit.
We dont have any. If it did it will look like this a(bc)
### Bracket Expressions
Brackets indicate a set of characters to match. Any individual character between the brackets will match.
### Greedy and Lazy Match
A Greedy match means that the regex engine (the one which tries to find your pattern in the string) matches as many characters as possible and Lazy' means match shortest possible string
### Boundaries
A word boundary is a position that is either preceded by a word character and not followed by one, or followed by a word character and not preceded by one.
### Back-references
Back-references are specified with backslash and a single digit (e.g. ' \1 ') , back-references are regular expression commands which refer to a previous part of the matched regular expression. 
### Look-ahead and Look-behind
Lookahead allows to add a condition for “what follows”. Lookbehind is similar, but it looks behind.
## Author
My name is Alex Canez i have an extensive background in telecomunications and i am now learning the web industry , follow my progress in my github :
```
https://github.com/AlexCan36
```
