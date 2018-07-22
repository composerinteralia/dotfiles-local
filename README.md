My customizations to complement https://github.com/thoughtbot/dotfiles
and https://github.com/thoughtbot/laptop

### Installation

```sh
curl -o "$HOME/.laptop.local" \
  --remote-name https://raw.githubusercontent.com/composerinteralia/dotfiles-local/master/laptop.local 
curl --remote-name https://raw.githubusercontent.com/thoughtbot/laptop/master/mac
```

Review the scripts and then run:

```sh
sh mac 2>&1 | tee ~/laptop.log
```
