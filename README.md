# Simple folder for some dotfiles

Need to manually symlink when installing on a new computer. Consider using something like https://github.com/anishathalye/dotbot if things get more complicated.

```fish
mkdir Developer
cd Developer
mkdir github
cd github
git clone https://github.com/morberg/dotfiles.git
cd ~/.config
ln -s ~/Developer/github/dotfiles/karabiner.edn
```
