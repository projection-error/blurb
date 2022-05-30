.

<div align="left">
  <img height=200 src=https://user-images.githubusercontent.com/84434778/170909913-5bb35b43-2e97-4805-b13f-5610340b1b0e.png><br>
</div>

-----------------
# blurb - explore the numeronyms of a wordset
Python package for exploring numeronymic properties of wordsets. For example:
- Finding the subset of a wordset which bear a common numeronym
  - For example, "k3k" could equivalently represent:
    - kayak
    - kiosk
    - klick
    - knack
    - knock
- Finding the numeronyms of a wordset that are unique and collision-free
  - For example, the _only_ word that can be uniquely compressed into "b3b" is "blurb". 
  - For example, the _only_ numeronym which starts and ends with "b" (e.g. "bxb") without collisions is "blurb"
- Analyze the frequency of collisions



## Motivation
I was thinking about the <a href=https://en.wikipedia.org/wiki/Numeronym>numeronym</a> of the venture capital firm Andreessen-Horowitz. "a16z" is used to identify the company, including their twitter handle.

```
A  N  D  R  E  E  S  S  E  N  H  O  R  O  W  I  T  Z

A  1  2  3  4  5  6  7  8  9  10 11 12 13 14 15 16 Z

A16Z
```

The interesting thing about this shorthand is that it represents a <a href=https://en.wikipedia.org/wiki/One-way_compression_function>compression function</a>. This is adjacent to the concept of a hash function in cryptography. Note that these are general usages of the terms - in more rigorous contexts there would be objection to this classification.

When selecting a hash function, it is imperative that it be collision-free. Could the numeronym act as a cryptographic hash function? 

The answer is absolutely not - I'll show you in the mouse scrolls to follow. 

However, there are some exceptions. Numeronyms may be good candidates for a cipher by leveraging the prevalence of collisions.

This python package will be considered successful if it can be used to make either Marc Andreessen or Ben Horowitz chuckle.

## Install
todo

## What is it and what can it do?

**blurb** is a Python package that provides the following classes and functions. Examples are shown below.


## Some observations from analyzing a large English wordset?
todo

## Dependencies
todo

## License
[BSD 3](LICENSE)



