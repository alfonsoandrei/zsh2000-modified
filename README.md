### ZSH2000-node

Forked from [consolemaverick](https://github.com/consolemaverick/zsh2000)

#### Installation

Create symbolic  link:
1. Clone repository
```sh
git clone  git@github.com:alfonsoandrei/zsh2000-node.git ~/.zsh2000-node
```

2. Create symbolic link
```sh
ln -s ~/.zsh2000-node/zsh2000.zsh-theme ~/.oh-my-zsh/themes/zsh2000-node.zsh-theme
```

3. Update your `.zshrc` file
```sh
nano ~/.zshrc
```

Find the line that sets the `ZSH_THEME`
```sh
ZSH_THEME="zsh2000-node"
```
4. Save the file and restart your terminal or run:
```sh
source ~/.zshrc
```

#### Changes

- Left prompt text color changed to black
- Prompt directory path will only go 2 deep
- Displays current Node version
