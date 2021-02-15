.dotfiles
=========

My config files. Mostly copied from <a href='https://github.com/jonkan/.dotfiles.git'>Jonkans dotfiles</a><br>

# Setup:

Install <a href="https://ohmyz.sh/">Oh my zsh</a>

Add the following to your .zshrc-file:

```
for file in ~/.dotfiles/.{exports,aliases,functions,private}; do
        [ -r $file ] && [ -f $file ] && source $file
done
unset file
```

Recommended theme: <a href='https://github.com/romkatv/powerlevel10k'>Power10k</a><br>

Some nice plugins
- https://github.com/zsh-users/zsh-autosuggestions
- https://github.com/zsh-users/zsh-syntax-highlighting
