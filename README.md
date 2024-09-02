This project contains the code used to generate the explanatory math videos found on [3Blue1Brown](https://www.3blue1brown.com/).

This almost entirely consists of scenes generated using the library [Manim](https://github.com/3b1b/manim).  See also the community maintained version at [ManimCommunity](https://github.com/ManimCommunity/manim/).

Note, while the library Manim itself is open source and under the MIT license, the contents of this project are intended only to be used for 3Blue1Brown videos themselves.

Copyright © 2022 3Blue1Brown

## [Instructions To Run](https://github.com/djsamseng/videos/tree/djsamseng-patch-1)

## Electric field is a sum of the Lorentz/Coulumb Forces from all particles
```python3
return sum(
    lorentz_force(
        points, charge,
        radius=self.radius_of_suppression,
        c=self.c
    )
    for charge in self.charges
)
```
[code](https://github.com/3b1b/videos/blob/c31dbd993c4b2136cfd7533fd38687f13aa034fe/_2023/optics_puzzles/objects.py#L771)

- If have this return a vector of zeros, the field no longer appears
  
