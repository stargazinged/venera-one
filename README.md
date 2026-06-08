

# venera-one
[![flutter](https://img.shields.io/badge/flutter-3.41.4-blue)](https://flutter.dev/)
[![License](https://img.shields.io/github/license/stargazinged/venera-one)](https://github.com/stargazinged/venera-one/blob/master/LICENSE)
[![stars](https://img.shields.io/github/stars/stargazinged/venera-one?style=flat)](https://github.com/stargazinged/venera-one/stargazers)

[![Download](https://img.shields.io/github/v/release/stargazinged/venera-one)](https://github.com/stargazinged/venera-one/releases)
[![AUR Version](https://img.shields.io/aur/version/venera-bin)](https://aur.archlinux.org/packages/venera-bin)
[![F-Droid Version](https://img.shields.io/f-droid/v/com.github.wgh136.venera)](https://f-droid.org/packages/com.github.wgh136.venera/)

A comic reader that support reading local and network comics.

## Fork maintenance
This fork keeps the original project usable for personal daily reading after upstream maintenance stopped.

### 1.6.4
- Fixed a reader bug where network comics marked as downloaded became unreadable after their local downloaded files or directories were moved or removed.
- The reader now verifies local files before using downloaded chapters and falls back to the original comic source when local files are unavailable.
- Fixed local `file://` image loading and local cover fallback path handling.

## Features
- Read local comics
- Use javascript to create comic sources
- Read comics from network sources
- Manage favorite comics
- Download comics
- View comments, tags, and other information of comics if the source supports
- Login to comment, rate, and other operations if the source supports

## Build from source
1. Clone the repository
2. Install flutter, see [flutter.dev](https://flutter.dev/docs/get-started/install)
3. Install rust, see [rustup.rs](https://rustup.rs/)
4. Build for your platform: e.g. `flutter build apk`

## Create a new comic source
See [Comic Source](doc/comic_source.md)

## Thanks

### Tags Translation
[EhTagTranslation](https://github.com/EhTagTranslation/Database)

The Chinese translation of the manga tags is from this project.

## Headless Mode
See [Headless Doc](doc/headless_doc.md)
