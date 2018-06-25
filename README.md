# `watch` addon for [todotxt-cli]

Clear terminal and repeat a todo command whenever the todo.txt file changes.

## Install

```
pip install watchdog
git clone https://github.com/kynda/todo.txt-watch.git
ln -s todo.txt-watch/watch $TODOTXT_ACTIONS_DIR/watch
ln -s todo.txt-watch/w $TODOTXT_ACTIONS_DIR/w
```

## Usage

```
Usage
  $ todo.sh watch [COMMAND]
             
  Examples"
    \$ todo.sh $(basename $0) "ls +project"
    \$ todo.sh $(basename $0) "lsp @context"
```

## License
GPL3

[todotxt-cli]: https://github.com/todotxt/todotxt-cli
