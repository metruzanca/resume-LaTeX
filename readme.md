## Getting started

### Using Docker
To use this repo, open it in a vscode dev container.
From the command pallete use the `Remote-Containers: Open Folder in Container` option.

If its your first time opening this repo, you'll need to run `latex build` and `view latex pdf` either from TeX sidebar or from command palette (make sure to have the resume.tex file open and in focus, not this readme)

After the first time, the PDF should automatically open to the right. Upon opening this project in the devcontainer.

### No Docker
Install the following dependecies from 
- latex-mk (*latexmk on some distros*)
- texlive-bin (*texlive*)
- texlive-latexextra (*texlive-latex-extra*)

Then install the Latex Workshop vscode extension.

If windows, do some googling for the same three packages or follow the guide on Latex Workshop's github page.