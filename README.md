# biiont's persoanl xetex styles

This is personal xetex styles.

## Installation

Before installation need to configure local texmf directory placement. Add following line to your shell profile (~/.bashrc or which is used by your shell) to move texmf to proper XDG location:
```
TEXMFHOME="${HOME}/.local/share/texmf"
```

Execute following commands to install it:
```
mkdir -p "${HOME}/.local/share/texmf/tex/xelatex"
cd "${HOME}/.local/share/texmf/tex/xelatex"
git clone git@github.com:biiont/texmf.git custom
```
