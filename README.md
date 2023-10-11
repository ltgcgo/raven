# raven

💨 Lightning-fast intuitive typing.

## Target scripts
* [Cyrillic](./cyrillic/)

## Usage
### `.mim` files
* Check if the IME framework of your system supports `m17n`. Most Linux desktop distros with IBus has `m17n` support included by default.
* Check if directory `~/.m17n.d/` exists for the current user. If not, create it via `mkdir ~/.m17n.d/`.
* Copy the `.mim` files you want to use to `~/.m17n.d`.
* Restart your IME framework.
  * If on IBus, run `ibus restart`.