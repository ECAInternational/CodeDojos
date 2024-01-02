## The Diamond Kata

### The Problem

We'd like you to complete Part 1 & 2 of the Diamond Kata as described below. Your solution should be in C# 

You can send the completed code to us as a zip file or a link to a public repository.

It may be helpful to consider the requirements of Part 2 when designing your solution for Part 1.

### Origin

This kata is based on a post by Seb Rose here: http://claysnow.co.uk/recycling-tests-in-tdd/

### Part 1

Given a character from the alphabet, print a diamond of its output with that character being the midpoint of the diamond.

Examples

    > diamond.exe A
      A

    > diamond.exe B
       A
      B B
       A

    > diamond.exe C
        A
       B B
      C   C
       B B
        A

Your solution should include appropriate tests and be able to cope with invalid user input.

It may be helpful visualise the whitespace in your rendering like this:

    > diamond.exe C
    _ _ A _ _
    _ B _ B _
    C _ _ _ C
    _ B _ B _
    _ _ A _ _

### Part 2

Modify your solution from Part 1 to sit behind an API endpoint that accepts a GET request with the character as a query string parameter and returns the diamond.

You should consider the end user of this API (probably a React front-end) and ensure that the format of the response will allow the front-end to render the diamond easily.