# obsidian-htmlexport
A pandoc template and custom CSS to produce HTML output with a responsive table-of-contents.

## Installation
The pandoc template goes in the `templates` subdirectory of the pandoc data directory.

* On linux/mac, this is usually `~/.config/pandoc/templates` or `~/.pandoc/templates`
* On Windows, this is usually `%AppData%\pandoc\templates`
* The pandoc data directory can be checked by running `pandoc --version`

The CSS file goes in a path relative to the Obsidian vault, the `.pandoc` subdirectory
is a good option.
