# LAD Based Film Transformation
Transformation of film scans based on normalising LAD patch values.

[Notebook](lad-based-film-transformation.ipynb)

**Introduction**

In the mid-1970s, Kodak introduced the Lab Aim Density, a standardised array of colour patches printed on the head of film reels, to calibrate and assess the accuracy of the colour of a given film print. This innovation would be recognised with a Technical Achievement Academy Award in 2001[^1]. 

While intended as a tool within the context of photochemical film duplication, it is also applicable in the digital space. This notebook uses common Python image processing tools to extract mean RGB information from LAD colour patches and interpolate a colour LUT, which could subsequently be applied to the entire film scan, normalising the material to a baseline film grade.

[^1]:https://www.oscars.org/sci-tech/ceremonies/2001

**License**

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)


