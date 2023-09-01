---
description: Learn how to concatenate string in bpp
---

# String concatenation

String concatenation is a fundamental operation in many programming languages, allowing you to join two or more strings together. In [BuckshotPlusPlus](https://bpplang.com/), string concatenation is achieved using the `+` symbol, making it intuitive and easy to combine strings or [variables](../data-types/variables.md).

## How it works

### Basic concatenation

To concatenate strings in [BuckshotPlusPlus](https://bpplang.com/), you simply place the `+` symbol between the strings or [variables ](../data-types/variables.md)you want to join.

Here's a basic example:

```
greeting = "Hello, "
name = "John!"
welcomeMessage = greeting + name  ## This will result in "Hello, John!"
```

## Use cases

1. **Dynamic Content**: Create dynamic strings based on user input or other variables.
2. **Code Organization**: Construct file paths or URLs dynamically to keep your code organized and maintainable.
3. **Text Processing**: Manipulate or format text by joining strings, prefixes, or suffixes.

## Important notes

* Ensure that the strings or variables you're concatenating are compatible. For instance, trying to concatenate a string with a non-string data type might result in errors.
* Use spaces or delimiters as needed when concatenating to ensure the resulting string is formatted correctly.
* Test your concatenated strings to ensure they produce the desired output, especially when used in critical parts of your application.
