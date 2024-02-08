---

# Madlibs Generator

## Introduction

This Python script serves as a Madlibs generator, allowing users to input specific words into a predefined story template. The program reads a story from a text file ("story.txt"), identifies placeholders denoted by angle brackets (<word>), prompts the user for input, and replaces the placeholders with the provided words to create a customized story.

## Instructions

1. Place your story template in a text file named "story.txt".
2. Run the Python script.
3. Enter words as prompted for each placeholder identified in the story.
4. Enjoy the personalized story generated with your input.

## Usage

```bash
python madlibs_generator.py
```

## Code Explanation

The script follows these main steps:

1. Reads the story template from "story.txt".
2. Identifies placeholders within angle brackets (<word>) in the story.
3. Prompts the user for input for each identified placeholder.
4. Replaces the placeholders with the user-provided words.
5. Prints the customized story.

## Example

Given the story template:

```text
In a <adjective> land, a curious <noun> collected <plural_noun>.
```

User input:

```bash
Enter a word for <adjective>: Enchanting
Enter a word for <noun>: Explorer
Enter a word for <plural_noun>: Mysteries
```

Output:

```text
In an Enchanting land, a curious Explorer collected Mysteries.
```

---
