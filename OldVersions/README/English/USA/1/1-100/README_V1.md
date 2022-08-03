
***

![/Matrix-lang_PlaceholderLogo.svg](/Matrix-lang_PlaceholderLogo.svg)

# [Matrix-lang](https://github.com/Matrix-lang/)
Matrix is a programming language with quotes and community posts related to the sci-fi series "The Matrix" this programming languages focuses solely on matrixes.

## [Original concept](/Concept/Matrix-lang-concept.txt)

Concept RGMatrix - A programming language focusing solely on matrixes

(Red, GREEN, Matrix) { alpha releases. RMatrix, beta releases: RGMatrix, full releases: update RGBMatrix: code blue }

The community and its posts will contain references to the Sci-Fi Matrix movie and game series.

There will be a game physics engine known as "String theory" which is based on the Matrix String Theory.

## [Syntax](/Matrix/Syntax/)

### [Comments](/Matrix/Syntax/COMMENTS.scmatrix)

Comments in Matrix are identical to comments in Python.

```python
# This is a comment
"""
This is a multi-
line comment.
"""
'''
This is also a
multi-line
comment.
'''
# Matrix comments follow the comment syntax of the Python programming language
```

### [Integers](/Matrix/Syntax/INTEGERS.scmatrix)

Integers in Matrix are inspired by Python's `int`

```python
# Integers
x = int(2)
y = integer(2) # Both int and integer do the same thing
z = (x + y) # Answer is 4
```

### [Matrixes/Matrices](/Matrix/Syntax/MATRIX.scmatrix)

The core feature of the language can be used like so:

```python
# Matrixes in Matrix
# This is the most important feature of the language. Everything will focus on this
# In this program, aba is the test matrix variable
# Start with this:
aba = matrix(type="multi-line" line-count=3); # Make sure to remember the hyphens, the spacing doesn't matter too much
# This is a multi-line Matrix. In this example, it is set to 3 lines
aba.xset(0); {0 1 2}
aba.xset(1); {1 2 3}
aba.xset(2); {2 3 0}
# You can put commas in the matrix parameters, but they are not required and will not change output
""" Considering: commas can act as space toggles, a comma could mean to put spaces, no comma would mean to not put spaces """
# xset is the value that sets the values of matrixes on a line of the matrix
# Now for output
aba.xout(0,2, exs=0);
# The output will be:
"""
0 1 2
1 2 3
2 3 0
"""
# however, you can also choose to disclude spaces by doing it like this (add the exs=1 line, 1 means on, 0 means off) exs stands for EXclude Spaces
aba.xout(0,2, exs=1);
# The output will be:
'''
012
123
230
'''
# This is a mix of ranges and matrixes
# This is just the basics of the Matrix command in the Matrix programming language
```

***

### [File info](/README.md)

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `1 (2022, Tuesday, August 2nd at 5:39 pm PST)`

**Line count (including blank lines and compiler line):** `139`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

_Note that on 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

**You may need special rendering support for the `<details>` HTML tag being used in this document**

</details>

***

### [File history](/OldVersions/README/)

<details><summary><p lang="en"><b>Click/tap here to expand/collapse the file history section for this project</b></p></summary>

<details><summary><p lang="en"><b>Version 1 (2022, Tuesday, August 2nd at 5:39 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Started the file
- [x] Added the title section
- [x] Added the `concept` section
- [x] Added the `syntax` section
- - [x] Added the `comments` subsection
- - [x] Added the `integers` subsection
- - [x] Added the `matrix` subsection
- [x] Added the `file info` section
- [x] Added the `file history` section
- [ ] No other changes in version 1

</details>

</details>

***
