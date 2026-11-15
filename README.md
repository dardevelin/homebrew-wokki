# Homebrew tap for clwokki

clwokki is Wokki's terminal client: voice and chat on Mumble servers from
the terminal, a status bar and the Mac's menu bar. Its releases, and what's
new in each, are on
[dardevelin/clwokki-releases](https://github.com/dardevelin/clwokki-releases/releases).

## Installing

- **macOS 27 or later**: `brew install --cask dardevelin/wokki/clwokki`.
  It installs `/Applications/clwokki.app` (Developer ID signed and
  notarized) and the `clwokki` command.
- **Linux** (glibc 2.35 or later), x86_64 or aarch64, with Homebrew on
  Linux: `brew install dardevelin/wokki/clwokki`. `brew services start
  clwokki` keeps its daemon running.

## Updating

clwokki still looks for a newer release once a day, and when its terminal
UI or menu bar opens, and says when one is out with the command to run:

- macOS: `brew upgrade --cask clwokki`
- Linux: `brew upgrade clwokki`

Then `clwokki restart` puts a running daemon on the new version.
