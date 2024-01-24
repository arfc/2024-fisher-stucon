# 2024-fisher-stucon

Holds Riley Fisher's abstract for the 2024 American Nuclear Society (ANS) Student Conference.


## Building the files

The document can be built by navigating to the ``abs/`` and running the following commands

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Alternatively, users on a unix system may run the ``make`` command in the ``abs/`` directory.
