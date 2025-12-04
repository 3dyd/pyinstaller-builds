# PyInstaller Builds

This repo builds PyInstaller compatible with Windows XP and above. Packages are aggregated within the [`latest`](https://github.com/3dyd/test-yt/releases/tag/latest) tag.

Vista+ build currently does not require patching of PyInstaller sources. Only build config needs to be adjusted (see [workflow file](.github/workflows/build-package.yml) for details).

XP+ build uses [3dyd/pyinstaller](https://github.com/3dyd/pyinstaller) fork patched for XP, see `*-xp`  branches there.

## How to Build

Fork repository. Go to `Settings` → `Pages` → `Build and deployment` and select `Source` → `GitHub Actions`.

Now you can build it using `Actions` → `build` → `Run workflow`.

If you want to build PyInstaller manually, some info can be found in the aforementioned `*-xp` branches `README.md` file.

## Credits

- [webcomics/pyinstaller-builder](https://github.com/webcomics/pyinstaller-builder)
- [yt-dlp/Pyinstaller-Builds](https://github.com/yt-dlp/Pyinstaller-Builds)
