# homebrew-gset

Homebrew tap for [GSET](https://github.com/Crazygiscool/GSETLang).

## Install

```bash
brew install crazygiscool/gset/gset
```

Upgrade:

```bash
brew update
brew upgrade gset
```

## Install from HEAD

```bash
brew install --HEAD crazygiscool/gset/gset
```

## Verify

```bash
gset --version
gset version
```

## Development

The formula is rendered from `packages/homebrew/Formula/gset.rb` in the
GSETLang repository by the `Publish Packages` workflow when a release is
published, so the version, source URL and checksum are stamped automatically.

To try a local change:

```bash
brew install --build-from-source --verbose crazygiscool/gset/gset
brew test crazygiscool/gset/gset
brew audit --strict crazygiscool/gset/gset
brew style crazygiscool/gset
```
