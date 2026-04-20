# About 
A collection of notes from my master degree in CS.

## Project structure 
To ease mantaining the project we choosed to use the `subfiles` package; 
as a consequence of this choice the project structure became the one following. 
```
    root/
      |-extra/
      |-src/
        |-sections/
        |-main.tex 
        |-main.pdf
```
Here `root` replaces the project directory, `extra` stores files such as `bib` 
    entries, images, etc. Lastly, `sections` stores the content of each `\section`,
    `\subsection` and `\subsubsection`, each in their own directory. 
    A `TikZ` directory will also be present to menage all `TikZ`, `listings`, etc.

## About the bibliography 
Although we provide no paper directly, we try to give the referece to it either in the 
PDF file or via the entries in `extra/BibTeX/`. If found, the `DOI` is also provided.
void any legal issues with unauthorized use of the papers and to properly credit the authors. 
