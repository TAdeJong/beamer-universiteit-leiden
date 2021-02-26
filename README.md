# beamer-universiteit-leiden
![example image](https://github.com/TAdeJong/beamer-universiteit-leiden/blob/master/graphics/example.png)
An unofficial LaTeX beamer template for scientific presentations in Universiteit Leiden layout, as described on [their website](https://huisstijl.leidenuniv.nl/en/). 

A working example showcasing some of the functionality is provided in [minimal.tex](minimal.tex).

A [matplotlib-style file](leidenuniv.mplstyle) is provided. Put the file in the same directory as you plotting code and add the following to the plot script to use:
```
import matplotlib.pyplot as plt
plt.style.use('./leidenuniv.mplstyle')
```


## Requirements
- Any presentation needs to be compiled using `xelatex` in order to support the fonts.
- Recent version of FontSpec to enable font-fallback.
- The fonts *Vestula* or *Minion* are recommended for layout, but can not be redistributed.
