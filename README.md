# latex_example
Template for LaTeX documents

The repository contains three base .tex files - zavrsni.tex, seminar.tex, diplomski.tex, which have a different content structure. 
Please leave only the base file that corresponds to your work, and delete the other two base .tex files. For example, if you are 
writing a Bachelor Thesis leave zavrsni.tex, and delete both seminar.tex and diplomski.tex.

The accompanying Latex Tutorial presentation can be found [here](Latex_Tutorial_Presentation.pdf).


### Using templates in English
If you want to use the templates in English, you need to make 3 changes in selected template file:
1. `\documentclass[times, utf8, zavrsni]{fer}` -> `\documentclass[times, utf8, zavrsni]{fer-eng}`
1. `\usepackage[croatian]{babel}` -> `\usepackage[english]{babel}`
1. `\bibliographystyle{fer}` -> `\bibliographystyle{fer-eng}`

### Changing citation style
The default citation style is (author, year). If you want to use numeric style, make the following change:

`\documentclass[times, utf8, zavrsni]{fer}` -> `\documentclass[times, utf8, zavrsni, numeric]{fer}`