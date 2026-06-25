# homebrew-tap

Homebrew tap for [MacBroom](https://github.com/afatihyavasi/MacBroom) — a safe,
open-source AI & system cache cleaner for the macOS menu bar.

## Install

```bash
brew install --cask afatihyavasi/tap/macbroom
```

That's it — the 🧹 icon appears in your menu bar.

> **Unsigned build:** 1.0.0 has no Apple Developer ID yet, so macOS quarantines
> it. On first launch, right-click MacBroom → **Open**, or clear it once:
>
> ```bash
> xattr -dr com.apple.quarantine /Applications/MacBroom.app
> ```
>
> Notarized releases will open with no prompt.
