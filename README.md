# Dotfiles 

Personal Linux configuration managed with [chezmoi](https://www.chezmoi.io/).

## Chezmoi Commands

| Task | Command |
|---|---|
| Edit configuration | `chezmoi edit ~/.zshrc` |
| Check changes | `chezmoi status` |
| Preview changes | `chezmoi diff` |
| Apply changes | `chezmoi apply` |
| List managed files | `chezmoi managed` |
| Open source directory | `chezmoi cd` |
| Update from GitHub | `chezmoi update` |

## Git Commands

| Task | Command |
|---|---|
| Check status | `git status` |
| Stage changes | `git add .` |
| Commit changes | `git commit -m "Update dotfiles"` |
| Push to GitHub | `git push` |

## New Machine Setup

Install Git and chezmoi:

    sudo apt install git
    sudo snap install chezmoi --classic

Initialize repository:

    chezmoi init https://github.com/USERNAME/dotfiles.git

Preview and apply:

    chezmoi diff
    chezmoi apply

*Minimal tools. Clean configs. Reproducible setups.*
