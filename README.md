# homebrew-harf

Homebrew tap for [Harf](https://github.com/alialhawas/Language-changer) — a macOS
menu-bar app that fixes text typed with the wrong keyboard layout, Arabic and
English.

```sh
brew tap alialhawas/harf
brew install --cask alialhawas/harf/harf
```

Homebrew 6 will not load a cask from a tap outside its own index until you trust
it. Installing by the fully qualified name *is* the trust, scoped to this one
cask — so no `brew trust` step is needed. If you would rather trust the whole
tap and use the short name, `brew trust alialhawas/harf` then `brew install
harf` does that instead.

Harf is not notarised by Apple yet, so macOS refuses it the first time. Allow it
once under **System Settings → Privacy & Security → Open Anyway**, which leaves
Gatekeeper on for everything else.

It then needs **Accessibility** and **Input Monitoring**. Neither is optional,
and both are powerful: read what the app does before granting them.
