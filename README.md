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
will store all the different sections from the `simple` ones 
(in terms of TeX this are the `\section`), then the `sub` ones (`\subsection`),
and so on. This is done because the `subfile` package is used.
Lastly, `extras` will store all additional files, from `Tikz` pictures to `BibTeX` files 
or anything else might be needed.

### About extras
The `extras` directory will store material that is available publicly, 
this means that papers, datasets, and everything else used as source material
that is not publicly available will not be present.

### The bibliography
Despite we don't provide papers directly, this should be avoided, 
each of the refereces will provide the correspoing DOI. This is done for two reason:
avoid any legal issues with unauthorized use of the papers and to properly credit the authors. 
