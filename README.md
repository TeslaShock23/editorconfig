# Introduction

This repository holds the `.editorconfig` file used throughout the codebase. It introduces a standardization of coding styles to minimize massive Pull Request diffs, as well as to make it easier to read other developer's code.

This repository will be linked to all other repositories as a submodule. That means whenever this repo gets updated, all other repos will automatically recieve the changes.

# Usage

Ensure that your global .gitconfig has the `submodule.recurse` key set to `true` using the following CLI command:

`git config --global submodule.recurse true`

This will ensure that the submodule gets updated whenever a pull on the parent repo occurs.
