# Reelyard Homebrew tap

Install [Reelyard](https://github.com/Reelyard/server) on macOS:

```sh
brew install --cask reelyard/tap/reelyard
reelyard install --user && reelyard start --user
```

Then open http://localhost:8787. Update with `brew upgrade --cask reelyard`.

The cask in `Casks/` is written by Reelyard's release workflow (GoReleaser); don't edit it by hand.
