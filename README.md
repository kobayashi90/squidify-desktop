# Squidify Desktop

Electron-based desktop app for Squidify, with background playback, tray controls and Discord presence, no browser required.

## What is Squidify?

[Squidify](https://www.squidify.org) is a free public music streaming service with a vast collection of anime, video game, movie and TV soundtracks.

Under the hood it runs on [Navidrome](https://www.navidrome.org/), an open source music server. Navidrome speaks the popular [Subsonic](https://www.subsonic.org/) protocol, which is why Squidify works in any browser, on mobile, and in every Subsonic-compatible client out there.

This app wraps the Squidify web player in an Electron-based desktop shell:

- Keeps playing in the background with tray controls
- Now-playing toast notifications
- Discord Rich Presence
- Switch between `squidify.org` and the `squidify.net` mirror if one is unreachable

## Download

Grab the latest build from the
[Releases page](https://github.com/kobayashi90/squidify-desktop/releases):

- **Linux** — AppImage and Flatpak
- **Windows** — NSIS setup and MSI
- **macOS** — x64 and arm64 (dmg)
- **Android** — signed release APK. The APK inlines build credentials, so it is
  distributed as a sideload-only build and is not attached to the public release;
  ask for the current private download link.

## Links

- 🎵 [Squidify](https://www.squidify.org) (mirror: [squidify.net](https://www.squidify.net))
- 📖 [Docs](https://docs.squidify.org/)
- ❤️ [Donate](https://give.calibour.com/donate/45bcfe59a820ac1e501e52d15474c89b), keep the service running
- 🐛 [Report an issue](https://github.com/kobayashi90/squidify-desktop/issues)
