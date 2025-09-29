# ABOUT
This repository serves as storage for various notes (WIP) I took while in college.
They are everything but a professional work, 
for this reason one should only use them just to recall the concepts.

## Projects structure
Each directory will have the following structure:
```
    root/
      |-main/
      |-sections
      |     |-simple/
      |     |-sub/
      |    ...
      |-extras/
      |     |-Tikz/
      |    ...
```
Here `root` referes to the project directory, `main` will store the PDF and the 
main TeX document from wich the all project should be built; `sections`
is will store all the different sections from the `simple` ones 
(in terms of TeX this are the `\section`), then the `sub` ones (`\subsection`),
and so on. This is done because the `subfile` package is used.
Lastly, `extras` will store all additional files, from `Tikz` pictures to images 
or anything else might be needed.

### About extras
The `extras` directory will store material that is available publicly, 
this means that papers, datasets, and everything else used as source material
that is not publicly available will not be present.

### The bibliography
Tho the motive above, each project will provided the DOI for each of the souces.
For those publicly available (at date of publication) a link to the paper will also be provided,
for the other just the references to the author/s and the title.
