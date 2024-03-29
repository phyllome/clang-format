# clang-format
Clang format file for embedded c projects

## Installation

* Change directory to project root.

* Add submodule in folder: `git submodule add git@github.com:phyllome/clang-format.git .clang`

* Create symbolic link (OSX/Linux): `ln -s .clang/.clang-format`
* Create symbolic link (Windows): `mklink .clang-format .clang\.clang-format`

* Add symbolic link (`.clang-format`) to `.gitignore` (OSX/linux terminal `echo ".clang-format" >> .gitignore`)

## VS Code

clang-format is supported out of the box by the C/C++ extension in VS Code. As long as the `.clang-format` file is present in the root directory, all subdirectories will inherit it.  Formatting is invoked by pressing  ⇧⌥F (osx) additionally you can modify the vscode settings `editor.formatOnSave` and `editor.formatOnType` for continuous formatting.
