# Flatten Array

Take a nested list and return a single flattened list with all values except nil/null.

The challenge is to write a function that accepts an arbitrarily-deep nested list-like structure and returns a flattened structure without any nil/null values.
 
For Example

input: [1,[2,3,null,4],[null],5]

output: [1,2,3,4,5]


## Loading your exercise implementation in PolyML

```
$ poly --use {exercise}.sml
```

Or:

```
$ poly
> use "{exercise}.sml";
```

**Note:** You have to replace {exercise}.

## Running the tests

```
$ poly -q --use test.sml
```

## Feedback, Issues, Pull Requests

The [exercism/sml](https://github.com/exercism/sml) repository on
GitHub is the home for all of the Standard ML exercises.

If you have feedback about an exercise, or want to help implementing a new
one, head over there and create an issue. We'll do our best to help you!

## Source

Interview Question [https://reference.wolfram.com/language/ref/Flatten.html](https://reference.wolfram.com/language/ref/Flatten.html)

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.
