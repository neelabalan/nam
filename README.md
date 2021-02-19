# nam (not a manpage)
> ( man->nam )

> I had a look at `cheat.sh`, `cheat` and `tldr` but wanted something simpler

### getting started

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

