# dotfiles
Storing my personal dot files for convenience in case I need to set up a new workspace.

## Example usage
1. Download this repository
2. Make symlinks from the files in this repository to your home directory (`~`)

For example:
```
ln -s ~/workspace/dotfiles/src/.zshrc ~/.zshrc
```
OR
```
ln -s ~/workspace/dotfiles/src/vscode/settings.json ~/Library/Application\ Support/Code/User/settings.json
```

3. Set up `~/.gitconfig.local` for all secret keys and personal information

For example:
```
[user]
        name = Austin Carrillo
        email = email@email.com

[github]
	user = acarrillo2
	token = SUPER_SECRET
```

