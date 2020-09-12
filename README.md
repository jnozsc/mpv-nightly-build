# mpv nightly build for macOS

![build](https://github.com/jnozsc/mpv-nightly-build/workflows/build/badge.svg)
![downloads](https://img.shields.io/github/downloads/jnozsc/mpv-nightly-build/total.svg?style=flat&labelColor=323940&color=brightgreen&logo=github)

## TL;DR

Download mpv nightly build for macOS [here](https://github.com/jnozsc/mpv-nightly-build/releases/latest)

## Describe the project you work on

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/perfume.png" alt="perfume" width="80%">

**Unofficial** [mpv](https://mpv.io/) nightly build for macOS.

I always want to recommend `mpv.app`  to my non-programming friends as the best third party video player on macOS.

However, mpv doesn't provide any official binary package.

I setup this automatical nightly job to build the latest version of `mpv.app` for people who prefer to download, drag it to `/Applications/` folder and enjoy their life.

## Q&A

### Why only for macOS, I need Linux, Windows... version

Well, I use `mpv.app` on macOS only.

### System requirements

A modern Macintosh machine officially supported by Apple.

[Vintage and obsolete products](https://support.apple.com/en-us/HT201624), Hackintosh or any other third-party patched macOS versions are untested, cannot and does not guarantee the functionality or performance.

### OS support

| macOS | version | compatibility |
| :------------- | -------------: | :-------------: |
| Big Sur | 11.0 | ❓ |
| Catalina | 10.15 | 🟢 |
| Mojave | 10.14 | 🟢 |
| High Sierra | 10.13 | 🟢 |
| Sierra | 10.12 | ❌ |
| Any older versions | < 10.12 | ❌ |

* 🟢 means compatible
* ❌ means incompatible
* ❓ means unknown

macOS, formerly known as OS X, does not have an official statement about its End-Of-Life policy. Based on [wikipedia](https://en.wikipedia.org/wiki/MacOS_version_history), it seems Apple only provides support to last 3 major release versions. So I try my best to support last 3 major release versions.

### Why nightly? I need the **stable** version

mpv does not release the stable version frequently, the stable release is created to [make Linux distributions happy](https://github.com/mpv-player/mpv#release-cycle).

###  "mpv" cannot be opened because the developer can not be verified

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/notarization_warning.png" alt="notarization_warning" width="50%">

macOS requires software to be [notarization](https://developer.apple.com/documentation/xcode/notarizing_macos_software_before_distribution) for security purposes. This process requires a $99 annual subscription plan. I don't have enough money for it.

There are at least 2 workarounds available

(1) You can hold your <kbd>⌥</kbd> aka <kbd>alt/option</kbd> key > right click the `mpv.app`, and then choose `open`

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/notarization_workaround_2.png" alt="notarization_workaround" width="50%">

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/notarization_workaround_3.png" alt="notarization_workaround" width="50%">

(2)
- from `Apple ` menu
- choose `System Preferences`
- click `Security & Privacy`
- then click `General`
- finally click `Open Anyway`

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/notarization_workaround.png" alt="notarization_workaround" width="50%">

### I download it, how can I change some settings

Place a `mpv.conf` in your `~/.mpv` folder, read the [manual](https://mpv.io/manual/master/) if you can. My configuration looks like [this](https://gist.github.com/jnozsc/99f62fd24b501ef78e8f).

### This does not work for me

Feel free to [open an issue](https://github.com/jnozsc/mpv-nightly-build/issues).


