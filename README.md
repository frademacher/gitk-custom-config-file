# Custom Config File Support for `gitk`
This repository contains a patched version of [`gitk`](https://github.com/git/git/tree/master/gitk-git) (as bundled with `git` 2.25.1) that enables to specify a custom config file on the commandline. This can be useful, e.g., to run `gitk` with a [dark theme](https://draculatheme.com/gitk) on an as-needed basis.

Usage:

```bash
gitk --custom-config=my-config
```