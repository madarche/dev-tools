Git and NPM dev-tools
=====================

Some dev tools (actually some shell scripts) to work on multiple Git
repositories and NPM modules arranged in a tree structure.


Available tools
---------------

* `gitr` : a recursive git command

    Runs the given Git command recursively in all the Git repositories located
    under the current directory and below.

* `npmr` : a recursive npm command

    Runs the given NPM command recursively in all the Git repositories being NPM
    modules (ie. they have a package.json file at their root) located under the
    current directory and below.

* `node_modules_rm`

    Deletes all the `node_modules` directories under the current directory and
    below.

* `package-lock_rm`

    Deletes all the `package-lock.json` files under the current directory and
    below.


Installation
------------

You can copy those scripts manually, or automatically have a symbolic links to
them from this Git repository to your `~/bin` directory through the provided
`install` script:

```shell
$ mkdir -p ~/bin
$ git clone https://github.com/madarche/dev-tools.git
$ cd dev-tools
$ ./install
```


