# template-latex-poly

A LaTeX template destined to be used for Master or PhD thesis redaction @ Polytechnique Montréal, Canada.

Feel free to adapt it to your needs, especially for the folders structure.

## Guidelines

- You can edit the packages you want to include or not in the `poly.sty` file, in "Packages" section. Be aware to not modify anything past that point (or at your own risks), otherwise the compilation might crash.
- I already put some of my macros (most of them are mathematics-related) in `maquereaux.sty`, but feel free to edit and put your own macros while you're writing your thesis !
- Be aware that you can't nest folders with the `\include` command, that's why there's a "chapters" folder but not more.
- To compile faster, I strongly advise you to comment the lines in the `\includeonly` command corresponding to parts you're not currently working on, so that the document compiles only the files you're working on and save build time.
