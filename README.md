# Tools

A collection of command line tools for macOS.


### clone-repo

Clone a github repo `https://HOST/OWNER/REPO` into `$GIT_ROOT/HOST/OWNER/REPO`.

- Environment variable `$GIT_ROOT` must be defined
- Folder `$GIT_ROOT` must exist
- If `HOST` contains a `www` prefix, it will be removed
- Folders `HOST` and `OWNER` will be created if they do not exist

For example:

Assuming `$GIT_ROOT` is set to `$HOME/git`, running either command:

`clone-repo https://github.com/chrisyunker/tools`

`clone-repo git@github.com:chrisyunker/tools`

will clone repo into directory:

`$HOME/git/github.com/chrisyunker/tools`


### kill-dock

Restart macOS Dock.


### toggle-dock

Toggle macOS Dock between left vertical and horizontal positions.

