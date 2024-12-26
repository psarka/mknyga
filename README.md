# Matematikos knyga

## Pasiruošimas

Įdiekite šiuos paketus knygos kompiliavimui

### Ubuntu

```shell
sudo apt install texlive-latex-extra asymptote texlive-lang-european
```

### Windows

TODO

## Kompiliavimas

```shell
python parse.py
latex knyga.tex
asy *.asy
latex knyga.tex
```