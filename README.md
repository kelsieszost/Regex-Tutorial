# Regex Expressions

## Summary

Regex Expressions allow us to search for specific patterns of text. Regex strings describe patterns to locate the position of text within a body of text. For example, we could create an expression that identifies all of the following names:

Mr. Schafer
Ms Davis
Mr T
Mrs Robinson

M(r|s|rs)\.?\s[A-Z]\w*

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

Anchors in regex expressions are used to match a position before or after characters. You will often need anchors to check if a sting fully matches a pattern. Anchors tell the regular expression where to start and end in a search. The following are examples of regex anchors:

^ = position at beginning of a string.
$ = position at end of a string

### Quantifiers

Quanitfiers in regex expressions are used to indicate how many instances of a character, group or character class are required to be present in an input for a match to be found. The following are examples of regex quantifiers:

* = matches zero or more times
+ = matches one or more times
? = matches zero or one time
{n} = matches exactly n times
{n,} = matches at least n times
{n, m} = indicates a range of values, in this case from n-m.

### OR Operator

The OR operator indicates that an instance can be either or. For example::

(r|s|rs) - the expression can contain r, s, or rs


### Character Classes

A character class defines a set of characters that can occurr within a string. The following are examples of character classes:

\d = a digit 0-9
\D = Not a digit 0-9
\w = word character matching 'a-z', A-Z', '0-9 and '__'
\s = whitespace character
\S = not a whitespace character


### Flags

A regex expression flag is an optional parameter that modifies its behavior of searching. It changes the default search behavior and makes it act in a different way. Examples of flags are the following:

i = ignore casing
g = global
s = dot all
m = multiline
y = sticky
u = unicode

### Grouping and Capturing

A group is represented by parentheses () and views everything within the parentheses as a single unit.
### Bracket Expressions

### Greedy and Lazy Match

Greedy match quantifiers search for as many intances of a character or group as possibile.
Lazy match quanifiers search for as little instances as possible. 

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
