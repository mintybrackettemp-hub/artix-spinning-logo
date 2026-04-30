# artix-spinning-logo

## Installation

First, git clone the baseline 3D renderer(you don't have to if already cloned)
```bash
git clone https://github.com/autopawn/3d-ascii-viewer.git ~/3d-ascii-viewer
```

Then, Download the Artix OBJ file
```bash
curl -O https://raw.githubusercontent.com/mintybrackettemp-hub/artix-spinning-logo/refs/heads/main/artix.obj -o ~/artix.obj
```

after that, in your shell config(commonly ~/.bashrc or ~/.zshrc) add the following
```
alias 'artixspin'='~/3d-ascii-viewer/3d-ascii-viewer ~/artix.obj'
```

After that just restart your shell/terminal, then type `artixspin` and look at that beautiful artix logo
