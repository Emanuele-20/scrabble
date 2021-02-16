# Scrabble

## Requirements 
Given a word, compute the scrabble score for that word.


## Letter Values
|Letter	|Value  |
|  :--: | :--:  |
A, E, I, O, U, L, N, R, S, T |	1
D, G	|2
B, C, M, P	|3
F, H, V, W, Y	|4
K	|5
J, X	|8
Q, Z	|10


## Acceptance Criteria
```
scrabble = new Scrabble('')
scrabble.score # => 0

scrabble = new Scrabble(" \t\n")
scrabble.score # => 0

scrabble = new Scrabble(null)
scrabble.score # => 0

scrabble = new Scrabble('a')
scrabble.score # => 1

scrabble = new Scrabble('f')
scrabble.score # => 4

scrabble = new Scrabble('street')
scrabble.score # => 6

scrabble = new Scrabble('quirky')
scrabble.score # => 22

scrabble = new Scrabble('OXYPHENBUTAZONE')
scrabble.score # => 41
```

## Input / Output exaple

Examples "cabbage" should be scored as worth 14 points:

- 3 points for C
- 1 point for A, twice
- 3 points for B, twice
- 2 points for G
- 1 point for E

And to total:

3 + 2x1 + 2x3 + 2 + 1

= 3 + 2 + 6 + 3

= 14