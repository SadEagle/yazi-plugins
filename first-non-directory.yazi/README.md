# first-non-directory.yazi

Jump to the first file ignoring directories.

## Disclamers and requirements

Tested only on Yazi 0.3.2 (3a2dd30 2024-09-01).

## Installation

```sh
ya pack -a lpanebr/yazi-plugins:first-non-directory
```

## Usage

Add this to your `keymap.toml` to set the keymap for the plugin:

```toml
[[manager.prepend_keymap]]
on   = [ "f", "j" ]
run  = "plugin --sync first-non-directory"
desc = "Jumps to the first file"
```