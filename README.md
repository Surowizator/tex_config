This is the LaTeX preamble I use in my projects. It is organised as a LaTeX package, hence the file structure.

## Usage

After adding this repository's root to the `TEXMF` variable or setting it as `TEXMFHOME` (for example by adding `export TEXMFHOME=/this/repository` to `.bashrc` and running `mktexlsr`) the preamble can be used by simply importing a package. Currently there are two preambles: `pres_preamble` is meant to be used in beamer presentations and `preamble` is the general-purpose one. `common` contains config common for the two.

Options available for `preamble`:
- `notes`: loads commands and settings I use for note-taking.
