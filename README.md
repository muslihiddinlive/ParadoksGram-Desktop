# ParadoksGram Desktop

Unofficial modified build of [Telegram Desktop](https://github.com/telegramdesktop/tdesktop) (base: v7.3.1) for Windows.
**This is not the official Telegram app and is not affiliated with Telegram.**

## Features

- **Ghost mode** — hide read receipts, typing status, online status and story views, with an optional daily schedule.
- *(in progress)* settings page, saved deleted messages, edit history, message ID display, sponsored-message hiding.

Settings are stored in `tdata/paradoks.ini`.

## Build

GitHub Actions builds `Telegram.exe` on every push to `main` (see `.github/workflows/paradoks-win.yml`).
Add `TDESKTOP_API_ID` and `TDESKTOP_API_HASH` repository secrets (from <https://my.telegram.org>) for a build that can log in;
without them the workflow uses test credentials.
Manual build instructions: [docs/building-win.md](docs/building-win.md).

## License

GPLv3 with OpenSSL exception, same as upstream — see [LICENSE](LICENSE) and [LEGAL](LEGAL).
Source: <https://github.com/muslihiddinlive/ParadoksGram-Desktop>.
