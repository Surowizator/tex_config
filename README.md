This is a LaTeX preamble I use in my projects. It is organised as a LaTeX package (the `preamble` package), hence the file structure.

## Usage

After adding this repository's root to the `TEXMF` variable or setting it as `TEXMFHOME` (for example by adding `export TEXMFHOME=/this/repository` to `.bashrc` and running `mktexlsr`) the preamble can be used by simply importing a package: `\usepackage[options]{preamble}`.

Available options:
- `notes`: loads commands and settings I use for note-taking.
