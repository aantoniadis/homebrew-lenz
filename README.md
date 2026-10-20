# Homebrew tap for Lenz

```sh
brew install aantoniadis/lenz/lenz
```

Installs the `lenz` command and its four apps from the [GitHub releases](https://github.com/aantoniadis/lenz/releases): `lenz-code` and `lenz-code-tui` (the code reader), and `lenz-diff` and `lenz-diff-tui` (the diff viewer, Git client and merge tool). On macOS they live inside `Lenz.app`. `lenz` opens the code reader, `lenz diff …` a comparison, and `--tui` the terminal version of either.

Upgrading from 0.0.1: comparisons now take the `diff` prefix (`lenz diff …`), and `lenz-tui` is now `lenz diff --tui`; update git difftool and mergetool settings to match (see the [README](https://github.com/aantoniadis/lenz#git-difftool)). The formula is maintained in the main repository at `packaging/homebrew/lenz.rb`.
