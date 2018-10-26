# Choosing the Correct Enumerables

## Learning Goals

- Assess knowledge of enumerables

## Introduction

Out of the box, Ruby provides us with a large variety of methods for iterating
over arrays. Some enumberables we've seen and used: `map`, `find`, and `sort`
are some examples.

Every enumerable has a specific task. While it is sometimes possible to use
enumerables interchangeably, choosing the _correct_ enumerable will lead
to code that is easier to read and understand.

Given the following array, choose the appropriate enumerable for the specific
task in each question

```ruby
array = ["And", "here", "were", "forests", "ancient", "as", "the", "hills,"]
```

**Question 1**: If we wanted to produce a new array where the characters of each
string are reversed, which enumerable would be best to use?

**Question 2**: If we wanted to confirm, TRUE or FALSE, if at least one
string in our array matched a regex expression, which enumerable should we use?

**Question 3**: What about the opposite? If we wanted to confirm, TRUE or FALSE,
if _not one_ of the strings in our array matched a regex expression?

**Question 4**: What if we wanted to confirm, TRUE or FALSE,
if _only one_ of the strings in our array matched a regex expression?

**Question 5**: What enumerable is best if we wanted to get the first 5
elements in an array?

**Question 6**: What enumerable is best if we wanted to remove the first 5
elements in an array?

**Question 7**: What if we wanted to remove all duplicates from an array?

**Question 8**: What if we wanted an enumerable that iterated over the whole
array as many times as we want?
