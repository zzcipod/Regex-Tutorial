# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Matching a URL – /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

## Table of Contents

- [Title (replace with your title)](#title-replace-with-your-title)
  - [Summary](#summary)
  - [Table of Contents](#table-of-contents)
  - [Regex Components](#regex-components)
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
  - [Author](#author)

## Regex Components

### Anchors

Anchors matches the characters anchors literally (case sensitive). Anchors can be global. Anchors can also be in multi lines, using ^ to begin and $ to end. In this case, ^ begin this string and end with a $.

### Quantifiers

In this case, ? matches the previous token between zero and one times, as many times as possible, giving back as needed (greedy). Same for the * and the second ? . {2,6} matches the previous token between 2 and 6 times.

### OR Operator

The logical OR (||) operator is typically used with boolean values. It is not used in this URL.

### Character Classes

In this case, [\da-z\.-] and [a-z\.] matches their single character present in the set.

### Flags

Regular expressions have optional flags that allow global searching and case-insensitive searching. These flags including 'd','g','i','m','s','u','y'.

### Grouping and Capturing

In this case, the capturing group is created by a rule in (). (https?:\/\/) is the first Captring group. Then ([\da-z\.-]+), then ( {2,6}), then ([\/\w \.-]*).

### Bracket Expressions

A bracket expression is an RE that shall match a specific set of single characters, and may match a specific set of multi-character collating elements. In this case, In this case, [\da-z\.-] and [a-z\.] matches their single character present in the set.

### Greedy and Lazy Match

In the greedy mode a quantified character is repeated as many times as possible. The lazy mode of quantifiers is an opposite to the greedy mode. It means: “repeat minimal number of times”.

### Boundaries

Boundary in Regex means the postion between \w- /W. In this case, we can find [\/\w \.-].

### Back-references

When N is the group number, a group can be referenced in the pattern using \N. we can use \k<name> to reference a named group.

### Look-ahead and Look-behind

Postitive Lookahead - Matches a group after the main expression without including it in the result. Negative Lookahead - Specifies a group that can not match after the main expression. Positive Lookbehind - Matches a group without including it in the result. Negative Lookbehind - Specifies a group that can not match before the main expression if there is a match it is discarded.

## Author

ZHICHONG ZHENG

https://github.com/zzcipod/Regex-Tutorial
