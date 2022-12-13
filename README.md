# Regex

## Summary

Regex, short for "regular expression," is a method used to search for patterns in text. It is often used in programming and can be a powerful tool for working with strings. Regular expressions use a set of symbols and syntax rules to find and match patterns in text, allowing you to search for, replace, and manipulate text efficiently and effectively. Regex can be used in many different programming languages and is a valuable skill for any programmer to have in their toolkit.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors
In regex, the anchor component is a special set of symbols that allow you to match patterns at specific positions in a string. For example, the "^" symbol is used to match the beginning of a string, while the "$" symbol is used to match the end of a string. These anchor components are useful for making sure that the pattern you are looking for is in the correct position in the string, and can help you to avoid false positives when searching for patterns in text. Overall, the anchor component is an important part of the regex syntax and is used to improve the precision and accuracy of your search patterns.
### Quantifiers
In regex, quantifiers are a special set of symbols that allow you to specify how many times a particular character, group, or character class should be matched in a string. For example, the "*" symbol is used to match zero or more occurrences of the preceding character or group, while the "+" symbol is used to match one or more occurrences. Quantifiers are an important part of regex syntax and can be used to make your search patterns more precise and accurate. They allow you to specify the exact number of times that a character or group should be matched in a string, which can help you to avoid false positives and ensure that your search patterns match the correct text.
### OR Operator
In regex, the OR operator is a special symbol that is used to match one of multiple possible patterns. The OR operator is represented by the vertical bar symbol "|" and is used to separate the different patterns that should be matched. For example, the regex pattern "cat|dog" would match any string that contains the substring "cat" or the substring "dog". The OR operator is a powerful tool in regex, as it allows you to match multiple patterns with a single regex pattern. It is often used in combination with other regex constructs, such as quantifiers and character classes, to create more complex and precise search patterns.
### Character Classes
In regex, character classes are a special type of pattern that allow you to match any single character from a set of predefined character groups. Character classes are defined using special syntax, and can be used to match a wide range of characters with a single regex pattern. For example, the character class "\d" is used to match any single digit (0-9), while "\s" is used to match any whitespace character (such as a space, tab, or newline). Character classes are an important part of regex syntax, as they allow you to match a wide range of characters with a single pattern, making your regex patterns more compact and efficient. They are often used in combination with other regex constructs, such as quantifiers and grouping constructs, to create more complex and precise search patterns.
### Flags
In regex, flags are a special type of modifier that allows you to change the behavior of the regex engine. Flags are specified using special syntax, and can be used to enable or disable certain features of the regex engine. For example, the "i" flag is used to perform a case-insensitive search, while the "g" flag is used to perform a global search that matches all occurrences of the pattern in the string. Flags are an important part of regex syntax, as they allow you to customize the behavior of the regex engine and fine-tune your search patterns. Different programming languages may support different sets of flags, so it's important to consult the documentation for the language you are using to see which flags are available.
### Grouping and Capturing
In regex, grouping constructs are a special set of symbols that allow you to group together multiple characters, patterns, or character classes. This is useful for creating more complex search patterns, and for applying quantifiers or other regex operations to a group of characters rather than a single character. Grouping constructs are an important part of regex syntax and can be used to improve the precision and flexibility of your search patterns. The most commonly used grouping constructs in regex are parentheses, which are used to group characters together. For example, the regex pattern "a(bc)*" would match any string that contains zero or more occurrences of the substring "bc" immediately after the letter "a".
### Bracket Expressions
In regex, bracket expressions are a special type of character class that allows you to match any single character from a set of characters. Bracket expressions are defined by enclosing a set of characters in square brackets, and can be used to match any single character that is listed in the brackets. For example, the regex pattern "[abc]" would match any single occurrence of the letters "a", "b", or "c" in a string. Bracket expressions are a powerful tool in regex, as they allow you to match a wide range of characters using a compact and easy-to-read syntax. They are often used in combination with other regex constructs, such as quantifiers, to create more complex and precise search patterns.

## Author
Payton Ray 
https://gist.github.com/PaytonRay/a343879386398ea1fd0845ec4ab60c6b
