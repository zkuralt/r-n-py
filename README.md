This is an example script for the RLadies meetup.

We will compare results created by the `DESeq2` R package and its Python implementation `pydeseq2`.

Some technicalities:
- `git clone git@github.com:zkuralt/r-n-py.git` will teleport this folder to your computer.
- Running renv::restore() will install all the R packages needed.

You should now be able to run the *example.Rmd* script without problems :)

Update:
Well, as usual, things did not go as smoothly as one would have wanted.
- Windows users had problems installing packages via `renv::restore()`, but manually installing packages mostly did the trick.
- Mac user had to explicitly set Python interpreter in the RStudio settings (Tools - Global options - Python).
- Linux user had no issues whatsoever :)


