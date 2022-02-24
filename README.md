# Module 17 Regex

gist the module 17 code description.

## Summary

 Matching an Email regex, or regular expression like this :  /^(([^<>()[\]\\.,;:\s@\"]+(\.[^<>()[\]\\.,;:\s@\"]+)*)|(\".+\"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/
used to validate email address. If a user is filling out a form on awebsite it will validate if the sequence is correct otherwise it'll thow and error,
this regex could be used to ask specifically for an email when one is requested by applications.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

### Anchors

Anchors are part of a family of tokens that do not match characxhters, they validate the sctrings structure elements are in the correct position.


### Quantifiers

Quantifiers match preciding elements once or as many times needed and specifies the instances of that charachter, a clas of the input must be given for a match to be found. 

### OR Operator
does not apply to this regex 

### Character Classes
Charachter classes are the most basic concept after a literal match, it makes a small sequence match a larger sequenece. the \d is used to find a single charachter and you can add more to match more digits in the email sequence.

### Flags
Floags are optional parameters that changes the way it searches in the regex of a regular expression, and it is denoted using a single lower case letter.


### Grouping and Capturing
Parenthesis are used to separate parts of a regex expression, and an @ symbol is place between the parts to separate thembut that can be avoided if you want to keep certains parts together in and prevent the regex from affecting certain parts of the expression.

### Bracket Expressions
Bracket Expressions is  a list of charachters enclosed by [] and search and matched for an type for data in that list for instance [a-z] would be searching for any letter in that range.


### Greedy and Lazy Match

These counter parts do what their names describe, the greedy match will try and match as much as possible and the lazy match as little as possible. 

## Author
 #### <a href="https://www.github.com/alanhernandezvillanueva">Alan Hernandez</a>
