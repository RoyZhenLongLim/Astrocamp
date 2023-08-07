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

## Exercises
Here are a few exercises:
1. Find a paper on ADS and add to bibliography
  - Cite it

## Miscellaneous
Creating custom commands
- \#n refers to the n-th variable
```LaTeX
\newcommand{\newCommandName}[numberOfVariables]{newCommand}
\newCommand{\ddx}[1]{\frac{d #1}{dx}}
```
