# LaTeX
## Getting Started
1. Create a new account with [OverLeaf](https://www.overleaf.com)
  - OverLeaf is an online LaTeX Editor
  - Make sure to sign up using your UNSW email to get pro features
  - Helps simplify writing LaTeX files by automating compilation and providing autocomplete amongst another host of benefits
2. Create a new project
  - Past the contents of the template into the folder
3. Select Menu (top left corner of OverLeaf)
  - TeX Live version is 2021
  - Now your LaTeX file should compile :)


## Basics
You can type special commands by using \\.  
You can use the built-in autocomplete by pressing the tab  
To bring up a list of autocomplete options, press ctrl + space  

## Mathematical Typesetting

To access inline equations, write `$$ a^2 + b^2 = c^2 $$`  (this should output $a^2 + b^2 = c^2$)  
To access equations in blocks, use:
```LaTeX
\begin{equation}
  a^2 + b^2 = c^2
\end{equationn}
```


## Exercises
Here are a few exercises:
1. Find a paper on ADS and add it to the bibliography
  - Cite it

## Miscellaneous
Creating custom commands
- \#n refers to the n-th variable
```LaTeX
\newcommand{\newCommandName}[numberOfVariables]{newCommand}
\newCommand{\ddx}[1]{\frac{d #1}{dx}}
```
## Appendix
If you want more information, feel free to google or consult a [guide](https://www.rpi.edu/dept/arc/docs/latex/latex-intro.pdf)

The UNSW Physics LaTeX Report Template is provided for all non-research related reports

Here is a [list of useful mathematical symbols](http://tug.ctan.org/info/undergradmath/undergradmath.pdf)
