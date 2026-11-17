# Resume

This repo is for housing my resume.

## Build locally (NixOS)

```bash
nix shell nixpkgs#texlive.combined.scheme-full -c pdflatex -interaction=nonstopmode resume.tex
```
