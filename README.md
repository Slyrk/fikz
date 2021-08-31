Fikz
====

This is a minimally intrusive package that changes the default overlay behavior of the `tikz` commands `\draw`, `\fill`, `\filldraw`, `\clip`, and `\node` within the `beamer` document class to the `\onslide` behavior. As a consequence, the bounding box of any `tikzpicture` environment is fixed for the entire frame - hence the portmanteau fikz - which prevents images from "jumping around" from slide to slide. In any other document class, overlay specifications of those `tikz` commands are ignored, allowing the same source code of a `tikzpicture` with overlay specifications to be used both in a research presentation and the paper, or in lecture slides and the assignments.

Usage
-----
The package provides no commands. The default behavior is changed by simply loading the package.

License
-------
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License (https://creativecommons.org/licenses/by-sa/4.0/).