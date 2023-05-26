# iina-plugin-template

This repository is a template for creating IINA plugins using `iina-cli`.

`iina-cli` will generate plugins from this template based on users' choices.
It is not intended to be used directly.

`iina-cli` will do the following things:

- Download this repository.
- Render `.file-list` using Mastache.
- Copy all files in `.file-list` to the destination directory.
- Render all copied files using Mastache.
