# Regex-Tutorial

In this tutorial, you will be able to get a breakdown of what Regex does and how it relates to computer science and coding in this tutorial. You can see what each character means and how it fits into your code in the accompanying example.

## Summary
/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/ Regex (short for regular expression) is a set of special characters that developers use to build a search pattern. Regex is interpreted right to left. In the above code, these characters are permitted to be in a users’ email.


## Table of Contents
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Anchors
Regex uses anchors like and $. While $ should go at the end, ^ should go at the start.

## Quantifiers
Quantifiers are a set of characters that limit the strings of the email. In this example, + and {} would be quantifiers. If a user sees a +, it means that the pattern can be matched one or more times. For curly brackets, there are multiple definitions depending on how many characters are seen in the curly brackets. Using this example, users will see {2,6}. These numbers mean that the email has to have more than 3 numbers, and have less than 6 numbers.

## Character Classes
Character classes and character escapes are the two different kinds of character classes. The characters included in a square bracket are rendered invalid by a character escape using a backslash. It is applied in a literal sense. An escape can be thought of as a backslash in this instance. Any character found in the regex sequence is considered a member of a character class.

## Grouping and Capturing
The most common way to describe parenthesis in Regex is a subexpression. This indicates that by segmenting the characters, it will be simpler to read them. Three sets of parenthesis are included in this example. These components exist separately within the email itself.

## Bracket Expressions
Looking at the characters closely, you can see there is three sets of brackets. The character set is indicated by these brackets. Any character included within a set of brackets is included in the email. A few examples include [a-z] and [0-9]. Each bracket in this example corresponds to a section of the email.


### Author
Jayad Arshad https://github.com/Jayad619/Regex-Tutorial