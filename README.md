# Pilcrow

Pilcrow is a native macOS app that helps you become a better writer. It is a coach, not a
ghostwriter: it shows where the prose is weak and why, and leaves the rewriting to you.

This repository holds Pilcrow's downloads. It does not hold the source.

## Install

With Homebrew:

```sh
brew install --cask makyllc/tap/pilcrow
```

Or download the DMG from [Releases](https://github.com/makyllc/pilcrow-releases/releases), open
it, and drag Pilcrow to Applications.

Pilcrow needs an Apple silicon Mac with macOS 14 or newer. Intel Macs are not supported. The app is signed by Maky Software Inc,
LLC and notarized by Apple.

## Update

With Homebrew, run `brew upgrade --cask makyllc/tap/pilcrow`. Otherwise download the newer DMG.
Pilcrow does not check for updates by itself.

## Your writing

Pieces are Markdown files in a folder you choose, `~/Writing` unless you change it. Removing Pilcrow
never removes them. Pilcrow has no account, no server and no analytics.

Reviews use an AI you connect: a Claude Code login, a ChatGPT login through Codex, or an API key
kept in the macOS keychain. The text under review goes only to that provider.

## Help

Report a problem in [Issues](https://github.com/makyllc/pilcrow-releases/issues). Include the
version and build from Settings > About.

Pilcrow is MIT licensed. Dependency and font licenses are in the app under About.
