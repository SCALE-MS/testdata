# SCALE-MS test and data files

Data and inputs for tests and such that we are keeping out of the main software repository

Please organize files into sensibly-named directories.

Please use `README.md` (or `README.rst` files according to your preference)
to describe any suggestions or constraints on how files should be used.

This is a public repository, so please cite sources where relevant.

We don't have a normative usage pattern for this repository (yet),
but it seems useful to keep data files from bloating the main software
repository. If `git` seems like the wrong tool (or GitHub the wrong host),
we can migrate this in the future.

## Use as a git submodule

It can be convenient to access this repository as a submodule of another.
For a good introduction to git submodules, see
https://www.atlassian.com/git/tutorials/git-submodule

When updating this repository from a parent repository, don't forget to push
updates for both this and the parent repository (as described at the linked document).

For convenience, make a habit of updating parent repositories with
`git pull --recurse-submodules`.

When cloning a repository that includes submodules, use
`git clone --recursive`.