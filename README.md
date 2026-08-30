# homebrew-harf

Homebrew tap for [Harf](https://github.com/alialhawas/Language-changer) — a macOS
menu-bar app that fixes text typed with the wrong keyboard layout, Arabic and
English.

```sh
brew tap alialhawas/harf
brew trust alialhawas/harf     # Homebrew 6 requires this for taps outside its index
brew install harf
```

Harf is not notarised by Apple yet, so macOS refuses it the first time. Allow it
once under **System Settings → Privacy & Security → Open Anyway**, which leaves
Gatekeeper on for everything else.

It then needs **Accessibility** and **Input Monitoring**. Neither is optional,
and both are powerful: read what the app does before granting them.
