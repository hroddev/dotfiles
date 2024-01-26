# Dotfile backup

### 1. Create a folder dotfile in the $HOME path.

```bash
mkdir ~/dotfiles
```

### 2. After move the files dotfiles to the new folder.

```bash
mv .gitconfig .zshrc ~/dotfiles
```

### 3. Create a soft link in the original dotfiles path.

```bash
ln -s ~/dotfiles/.gitconfig ~/.gitconfig
ln -s ~/dotfiles/.zshrc ~/.zshrc
```

### 4. Init the Git dotfiles and Push the files to the Github repo.
