# PyInstaller Builds

| Minimum OS | Wheel | Source |
|-|-|-|
| Windows Vista | [pyinstaller-6.17.0-py3-none-any.whl](https://3dyd.github.io/pyinstaller-builds/vista/pyinstaller-6.17.0-py3-none-any.whl) | [pyinstaller-6.17.0.tar.gz](https://3dyd.github.io/pyinstaller-builds/vista/pyinstaller-6.17.0.tar.gz) |
| Windows XP | [pyinstaller-6.17.0-py3-none-any.whl](https://3dyd.github.io/pyinstaller-builds/xp/pyinstaller-6.17.0-py3-none-any.whl) | [pyinstaller-6.17.0.tar.gz](https://3dyd.github.io/pyinstaller-builds/xp/pyinstaller-6.17.0.tar.gz) |

[![build](https://github.com/3dyd/pyinstaller-builds/actions/workflows/build-package.yml/badge.svg)](https://github.com/3dyd/pyinstaller-builds/actions/workflows/build-package.yml)

This repo builds PyInstaller compatible with Windows XP and above.

Packages are rebuilt periodically. GitHub Releases section is not proper place to store short lifetime packages, so they are deployed to GitHub Pages instead. This also means they have  permanent links, so for example they can be listed at the top of this page.

Vista+ build currently does not require patching of PyInstaller sources. Only build config needs to be adjusted (see [workflow file](.github/workflows/build-package.yml) for details).

XP+ build uses [3dyd/pyinstaller `6.17.0-xp` branch](https://github.com/3dyd/pyinstaller/tree/6.17.0-xp) patched for XP.

## How to Build

Fork repository. Go to `Settings` → `Pages` → `Build and deployment` and select `Source` → `GitHub Actions`.

Now you can build it using `Actions` → `build` → `Run workflow`.

If you want to build PyInstaller manually, some info can be found in the aforementioned `6.17.0-xp` branch [readme](https://github.com/3dyd/pyinstaller/blob/6.17.0-xp/README.md).

## Credits

- [webcomics/pyinstaller-builder](https://github.com/webcomics/pyinstaller-builder)
- [yt-dlp/Pyinstaller-Builds](https://github.com/yt-dlp/Pyinstaller-Builds)
