# Git

Inspired by http://uberblo.gs/2010/12/git-lol-the-other-git-log particularly the top comment, I have tweaked my own `git lol`. 

```
git config --global --add alias.lol 'log --graph --decorate --abbrev-commit --all --date=local --pretty=\"%C(auto)%h%d %C(cyan)%an %C(green)%cd %C(red)%GG %C(reset)%s\" --date=local'
```
