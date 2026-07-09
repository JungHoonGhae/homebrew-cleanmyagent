# homebrew-cleanmyagent

Homebrew tap for [cleanmyagent](https://github.com/JungHoonGhae/cleanmyagent) —
audit what your coding agents' skills, plugins, and MCP servers cost
(context tokens every session) versus how much you actually use them.

## Install

```bash
brew tap junghoonghae/cleanmyagent
brew install cleanmyagent
```

## Upgrade

```bash
brew update && brew upgrade cleanmyagent
```

## Releasing (maintainer notes)

1. Tag a release in the main repo: `git tag vX.Y.Z && git push origin vX.Y.Z`
2. `curl -fsSL https://github.com/JungHoonGhae/cleanmyagent/archive/refs/tags/vX.Y.Z.tar.gz | shasum -a 256`
3. Update `url` and `sha256` in `Formula/cleanmyagent.rb`, commit, push.
