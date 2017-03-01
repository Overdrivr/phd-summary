# Phd Summary in french

Original document is [here](https://github.com/Overdrivr/PhD)

## Autocorrect with hunspell

* Install from [here](https://sourceforge.net/projects/ezwinports/files/)
* Download french dictionnary [here](http://www.dicollecte.org/home.php?prj=fr)

Configure everything according to [this post](https://lists.gnu.org/archive/html/help-gnu-emacs/2014-04/msg00030.html)

To check chapter 1, run from inside the `src` folder the following command

```
hunspell -t -i UTF-8 -d fr-toutesvariantes chap1.tex
```

On Windows, to spell check all relevant files

```
spellcheck.md
```
