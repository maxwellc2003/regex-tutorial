# Email validation regex

Welcome to my regex tutorial, I will be providing an example of a regex and how it is used.

## Summary

The regex I will be describing is a regex that validates if the text input is in correct email format

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

^[\w-\.]+@([\w-]+\.)+[\w-]{2,4}$

### Anchors

^abc$	start / end of the string
\b\B	word, not-word boundary

USE:
"^" Beginning.
"$" End.

### Quantifiers

a{5}a{2,}	exactly five, two or more
a{1,3}	between one & three
a+?a{2,}?	match as few as possible
ab|cd	match ab or cd

### OR Operator

a*a+a?	0 or more, 1 or more, 0 or 1

### Character Classes

.	any character except newline
\w\d\s	word, digit, whitespace
\W\D\S	not word, digit, whitespace
[abc]	any of a, b, or c
[^abc]	not a, b, or c
[a-g]	character between a & g

### Grouping and Capturing

(abc)	capture group
\1	backreference to group #1
(?:abc)	non-capturing group

### Bracket Expressions

[abc]	any of a, b, or c
[^abc]	not a, b, or c
[a-g]	character between a & g

### Look-ahead and Look-behind

(?=abc)	positive lookahead
(?!abc)	negative lookahead

## Author

My name is Maxwell Colby, I am a computer science student and at the time of this assignment, am currently enrolled in the UC Davis web development bootcamp.
My github is https://github.com/maxwellc2003