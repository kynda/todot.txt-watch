# `watch` addon for [todotxt-cli]

Clear terminal and repeat a todo command whenever the todo.txt file changes.

## Install

```
sudo apt install entr
git clone https://github.com/kynda/todo.txt-watch.git
ln -s todo.txt-watch/watch $TODOTXT_ACTIONS_DIR/watch
ln -s todo.txt-watch/w $TODOTXT_ACTIONS_DIR/w
```

## Usage

```
Usage
  $ todo.sh watch [COMMAND]
             
  Examples
    $ todo.sh watch ls +project
    $ todo.sh watch lsp @context
```

## License
GPL3

[todotxt-cli]: https://github.com/todotxt/todotxt-cli
