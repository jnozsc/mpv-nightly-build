# mpv nightly build for macOS

![mpv nightly build for macOS](https://github.com/jnozsc/mpv-nightly-build/workflows/mpv%20nightly%20build%20for%20macOS/badge.svg)

## TL;DR

Download mpv nightly build for macOS [here](https://github.com/jnozsc/mpv-nightly-build/releases)

## Describe the project you work on

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/perfume.png" alt="perfume" width="80%">

**Unofficial** [mpv](https://mpv.io/) nightly build for macOS.

I always want to recommend `mpv.app`  to my non-programming friends as the best video player on macOS.

However, mpv doesn't provide any official binary package. In addition, I don't like any existing 3rd party build.

I setup this nightly job to build the latest version for people who prefer to download, drag it to `/Application/` folder and enjoy their life.

## Q&A

### Why only for macOS, I need Linux, Windows... version

Well, I use `mpv.app` on macOS only.

### I am still on the previous major release of macOS/OSX, does it work?

| macOS | version | compatibility |
| :------------- | -------------: | :-------------: |
| Catalina | 10.15 | 🟢 |
| Mojave | 10.14 | 🟢 |
| High Sierra | 10.13 | 🟢 |
| Sierra | 10.12 | ❌ |
| Any older versions | < 10.12 | ❌ |

* 🟢 means compatible
* ❌ means incompatible

macOS, formerly known as OS X, does not have an official statement about its End-Of-Life policy. Based on [wikipedia](https://en.wikipedia.org/wiki/MacOS_version_history), it seems Apple only provides support to last 3 major release versions. So I try my best to support last 3 major release versions.

### Why nightly? I need the **stable** version

mpv does not give a F to stable release, the stable release is created to [make Linux distributions happy](https://github.com/mpv-player/mpv#release-cycle).

###  "mpv" cannot be opened because the developer can not be verified

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/notarization_warning.png" alt="notarization_warning" width="50%">

macOS requires software to be [notarization](https://developer.apple.com/documentation/xcode/notarizing_macos_software_before_distribution) for security purposes. This process requires a $99 annual subscription plan. I don't have enough money for it.

There are at least 2 workarounds available

(1) You can hold your `⌥/alt/option` key > right click the `mpv.app`, and then choose `open`

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/notarization_workaround_2.jpg" alt="notarization_workaround" width="50%">

<img src="https://github.com/jnozsc/mpv-nightly-build/raw/master/asset/notarization_workaround_3.jpg" alt="notarization_workaround" width="50%">

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


