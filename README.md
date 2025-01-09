# vis-cursors ✍️

A [vis](https://github.com/martanne/vis) [plugin](https://github.com/martanne/vis/wiki/Plugins) for saving cursor position per file.

Default save path is `{XDG_CACHE_HOME|HOME/.cache}/vis-cursors.csv`.

Set a custom path with `M.path`.

Limit number of files/positions with `M.maxsize` (defaults to `1000`).

Cursor positions per file are ordered by the last used at the top of `vis-cursors.csv`.
