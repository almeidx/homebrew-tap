# almeidx Homebrew Tap

Homebrew formulae for `wpdiff`, `uatu`, and `cerebro`.

## Install

```sh
brew install almeidx/tap/wpdiff
brew install almeidx/tap/uatu
brew install almeidx/tap/cerebro
```

The formulae install prebuilt archives from each project's GitHub Releases.

## Maintenance

Regenerate formulae after publishing new CLI releases:

```sh
bin/update-formulae
```

The current published CLI releases include Linux musl assets. The upstream
release workflows are configured to add `aarch64-apple-darwin` assets starting
with the next release; rerunning the update script after those releases will add
macOS URLs automatically.
