# ohmyzsh cdn

## How to use

```bash
# curl
sh -c "$(curl -fsSL https://cdn.jsdelivr.net/gh/9CDN/ohmyzsh/curl.sh)"
# wget
sh -c "$(curl -fsSL https://cdn.jsdelivr.net/gh/9CDN/ohmyzsh/wget.sh)"
```

## Useful plugins

### zsh-autosuggestions
```bash
git clone https://github.com/9Fork/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
```bash
git clone git@github.com:9Fork/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
### zsh-syntax-highlighting
```bash
git clone https://github.com/9Fork/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
```bash
git clone git@github.com:9Fork/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## Set `.zshrc`

```
plugins=(
    git
    zsh-autosuggestions
    zsh-syntax-highlighting
)
```
