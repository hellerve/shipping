# shipping

A solution to the [shipping puzzle](https://kevinlynagh.com/notes/shipping-puzzle/)
from a blog post by Kevin Lynagh.

It takes about 3.5 seconds on my machine, and 75.9% of that time is spent in
`String.lines`, which splits a string into an array of lines.
