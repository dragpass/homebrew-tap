# DragPass Homebrew Tap

Homebrew tap for [DragPass Keeper](https://github.com/dragpass/keeper), the
native key-custody helper for the DragPass Chrome Extension.

## Install

```bash
brew install dragpass/tap/keeper
```

The formula installs the `dragpass-keeper` binary and registers the Chrome
Native Messaging manifest at the user level, so no administrator privileges
are required.

## How this tap is maintained

The formula in `Formula/` is generated and updated automatically by the
[keeper release workflow](https://github.com/dragpass/keeper/blob/main/.github/workflows/release.yml)
(GoReleaser) on every tagged release. Do not edit it by hand.
