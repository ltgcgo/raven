# raven

💨 Lightning-fast intuitive typing.

## Target scripts
* [Cyrillic](./cyrillic/)

## Usage
### For `m17n`
* Get the required `.mim` files.
* Check if the IME framework of your system supports `m17n`. Most Linux desktop distros with IBus has `m17n` support included by default.
* Check if directory `~/.m17n.d/` exists for the current user. If not, create it via `mkdir ~/.m17n.d/`.
* Copy the `.mim` files you want to use to `~/.m17n.d`.
* Restart your IME framework.
  * If on IBus, run `ibus restart`.

### For [Rime](https://github.com/rime)
#### Linux
* Get the required `.yaml` files. Check for files ending in `.schema.yaml`, `.dict.yaml` and `.custom.yaml`.
* Copy the `.yaml` files to `~/.config/ibus/rime/`.
* (Optional) Customize the new schema as you see fit.
* Enable the new schema in `~/.config/ibus/rime/default.custom.yaml`.
* Redeploy Rime via `touch ~/.config/ibus/rime/; ibus restart`.

#### Windows
* Get the required `.yaml` files. Check for files ending in `.schema.yaml`, `.dict.yaml` and `.custom.yaml`.
* Copy the `.yaml` files to `%APPDATA%\\Rime`.
* (Optional) Customize the new schema as you see fit.
* Enable the new schema in `%APPDATA%\\Rime\\default.custom.yaml`.
* Redeploy Rime via start menu or right-click menu of the taskbar icon.