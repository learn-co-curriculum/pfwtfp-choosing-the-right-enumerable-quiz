# Choosing the Correct Enumerables

## Learning Goals

- Assess knowledge of enumerables

## Introduction

Ruby provides us with a large variety of methods for working with `Arrays`.
These methods are called [Enumerable]s. Enumerables help us do very common
operations on `Arrays`: see whether one of the elements matches a test, see
whether all of the elements match a test, produce a new `Array` of elements
that matched some test, create a new `Array` that's been sorted, etc.

We can find a list of them in Ruby's [Enumerable] documentation.

Every `Enumerable` has a **specific** task. While it is sometimes possible to use
`Enumerable`s interchangeably, choosing the _correct_ `Enumerable` will lead
to code that is easier to read and understand.

Given the following `Array`, choose the appropriate `Enumerable` for the specific
task in each question. Feel free to look at the documentation to find the right
answer.

```ruby
array = ["And", "here", "were", "forests", "ancient", "as", "the", "hills,"]
```

**Question 1**: If we wanted to produce a new `Array` where the characters of each
string are reversed, which `Enumerable` would be best to use?

**Question 2**: If we wanted to confirm, TRUE or FALSE, whether at least one
`String` in our `Array` began with the letter 'c', which `Enumerable` should we
use?

**Question 3**: What about the opposite? If we wanted to confirm, TRUE or FALSE,
whether _one_ of the `String`s in our `Array` begins with 'c'?

**Question 4**: What if we wanted to confirm, TRUE or FALSE,
whether _one_ of the `String`s in our `Array` begins with 'c'?

**Question 5**: Which `Enumerable` is best if we wanted to get the first 5
elements in an `Array`?

**Question 6**: What `Enumerable` is best if we wanted to remove the first 5
elements in an `Array`?

**Question 7**: Which `Enumerable` should we use if we wanted to remove all
duplicates from an `Array`?

**Question 8**: What if we wanted an `Enumerable` that iterated over the whole
`Array` as many times as we want?

[Enumerable]: https://ruby-doc.org/core-2.3.1/Enumerable.html
