Checkout [cm](https://github.com/neelabalan/cm). This repository is now archived. I am no longer using this.


# nam (not a manpage)
> ( man->nam )
> I had a look at `cheat.sh`, `cheat` and `tldr` but wanted something simpler

![gif](https://i.imgur.com/HLEOrpV.gif)

### getting started

#### dependencies
- [fzf](https://github.com/junegunn/fzf)
- [bat](https://github.com/sharkdp/bat)

```bash
# download the script to your folder which added in PATH
# in my case it will be .scripts folder
wget https://raw.githubusercontent.com/neelabalan/nam/master/nam

# clone cheat repo to home dir and rename it
git clone https://github.com/cheat/cheatsheets.git && mv cheatsheets .nam
```

### how to 

```bash
nam

nam <command>

# to edit
nam -e <command>

# to bookmark the last 'n' command
nam -b 2 bookmark
```

> note: the function `nam` can be copied over to .bashrc if you don't want to include it in your PATH

