# Biiont's personal TeX styles

This is custom styles for TeX made by biiont. This styles designed to work with XeTeX mainly.

## Installation

In order to install this styles without root permissions you need to add following line to your shell profile (~/.bashrc or which is used by your shell) to move texmf to proper XDG location:
```
TEXMFHOME="${HOME}/.local/share/texmf"
```

Then restart your shell and execute following commands to install this styles:
```
cd "${HOME}/.local/share"
git clone git@github.com:biiont/texmf.git texmf
```
