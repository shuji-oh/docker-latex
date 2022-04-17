# docker-latex

The docker image to convert tex to pdf.

## usage

1. Run `docker build -t sititou70/latex .`
1. Download `latexmkrc `and `tex2pdf.sh` on directory there is target tex file.
1. Run `./tex2pdf.sh [tex file]`

## usage for apple silicon env

1. Run `docker build -f Dockerfile_AppleSilicon -t sititou70/latex .`
1. Download `latexmkrc `and `tex2pdf.sh` on directory there is target tex file.
1. Run `./tex2pdf.sh [tex file]`

## docker hub

[sititou70/latex](https://hub.docker.com/r/sititou70/latex/)
