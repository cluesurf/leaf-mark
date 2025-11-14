## To fix

- Leaf: should make SVG fit width of glyph, so basically tight-bounding
  box.
- Leaf: make into font too.
- Line: Missing angle brackets `<` and `>` it seems. Actually, remove
  brackets, too complicated for what it is, punctuation probably was
  scarce.
- Only punctuation: period.
- Remove dash `-`, comma `,`, and angle brackets `<` / `>`.
- Remove `10` as it's own thing.
- Period: should be horizontal leaf, aligned bottom.
- Vowels: leaf's should align bottom.
- Make sure all "leaf" glyphs are same width / leaf size in general.
- Note: vowels are only 2-leaves high, whereas consonants/numbers are
  5-leaves high.

## TODO for Specification

- Maybe 4-leaves per side for consonants would help distinguish better
  between numbers and consonants?

## To-Redo Some Glyphs

Going to make into this (mimicking the flow/walkthrough waving
back-n-forth through letters/sounds
[here](https://tune.surf/rule/tone)). Base structural outline is as
follows:

- 2-height: vowels
- 4-height: consonants
- 5-height: digits

```

  # 1 (full)
   h
  -|-
  -|-
  -|-
  -|-

  # 2 (4 down on one side at least)
   s    f         z    v         j    x         C    c
  -|-  -|-       -|-  -|-       -|-  -|-        |-  -|
  -|-  -|-       -|-  -|-        |-  -|        -|-  -|-
  -|-  -|-        |-  -|        -|-  -|-       -|-  -|-
   |-  -|        -|-  -|-       -|-  -|-       -|-  -|-

  # 3 (3 on one side)
   m    n    q           b    d    g          p    t    k
  -|-  -|-  -|-         -|-  -|-  -|-        -|-  -|-  -|-
   |-  -|-  -|           |    |    |          |-  -|-  -|
   |-  -|-  -|           |-  -|-  -|          |    |    |
   |    |    |           |-  -|-  -|          |-  -|-  -|

  # 4 (middle two missing)
   w    y    l    r
  -|-  -|-  -|    |-
   |    |    |    |
   |    |    |    |
  -|    |-  -|-  -|-

```

```

   i    e    a    o    u
  -|-  -|   -|-   |-  -|-
  -|   -|-  -|-  -|-   |-

```
