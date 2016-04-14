# git

Clone to `.gitconfig.d` directory

```
git clone git@github.com:pghalliday-dotfiles/git.git ~/.gitconfig.d
```

and create the `.gitconfig` config

```
cat > ~.gitconfig <<EOF
[include]
  path = .gitconfig.d/gitconfig
EOF
```
