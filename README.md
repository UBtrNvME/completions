# Custom Completions for ZSH Completions framework

ZSH uses `compinit` to work with completions

## Installation

```sh
git clone https://github.com/UBtrNvME/completions.git ~/.custom-completions && \
cat << EOF > ~/.zshrc
fpath=(
    ~/.custom-completions
    "\${fpath[@]}"
)
EOF
```

### List of working comletions

*   pyenv
