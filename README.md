# Merge log

Scroll down for the original README.md!

Base revision: 6811eda2b9eaceb79238ea3c2e3a5a43b86c6c6a

|Pull Request|Commit|Title|Author|Merged?|
|----|----|----|----|----|
|[6](https://github.com/citra-emu/citra-canary/pull/6)|[a53a8d3](https://github.com/citra-emu/citra-canary/pull/6/files/)|Canary Base (MinGW Test)|[liushuyu](https://github.com/liushuyu)|Yes|
|[3825](https://github.com/citra-emu/citra/pull/3825)|[6135931](https://github.com/citra-emu/citra/pull/3825/files/)|travis: share environment variables with Docker|[liushuyu](https://github.com/liushuyu)|Yes|
|[3804](https://github.com/citra-emu/citra/pull/3804)|[63f756a](https://github.com/citra-emu/citra/pull/3804/files/)|citra-qt: Improve Title Bar display|[zhaowenlan1779](https://github.com/zhaowenlan1779)|Yes|
|[3788](https://github.com/citra-emu/citra/pull/3788)|[9060e08](https://github.com/citra-emu/citra/pull/3788/files/)|shader/jit: implement breakc|[wwylele](https://github.com/wwylele)|Yes|
|[3787](https://github.com/citra-emu/citra/pull/3787)|[874cb42](https://github.com/citra-emu/citra/pull/3787/files/)|shader/jit: preserve integer & condition register across invocation|[wwylele](https://github.com/wwylele)|Yes|
|[3778](https://github.com/citra-emu/citra/pull/3778)|[781912e](https://github.com/citra-emu/citra/pull/3778/files/)|gl_rasterizer: implement shadow map 2D/Cube - Image load/store version|[wwylele](https://github.com/wwylele)|Yes|
|[3706](https://github.com/citra-emu/citra/pull/3706)|[b1858c2](https://github.com/citra-emu/citra/pull/3706/files/)|Use Travis CI to build MinGW packages|[liushuyu](https://github.com/liushuyu)|Yes|
|[3632](https://github.com/citra-emu/citra/pull/3632)|[523c52c](https://github.com/citra-emu/citra/pull/3632/files/)|Add Support for Stereoscopic 3D|[N00byKing](https://github.com/N00byKing)|Yes|
|[3617](https://github.com/citra-emu/citra/pull/3617)|[30c6c37](https://github.com/citra-emu/citra/pull/3617/files/)|QT: Add support for multiple game directories|[BreadFish64](https://github.com/BreadFish64)|Yes|


End of merge log. You can find the original README.md below the break.

------

**BEFORE FILING AN ISSUE, READ THE RELEVANT SECTION IN THE [CONTRIBUTING](https://github.com/citra-emu/citra/blob/master/CONTRIBUTING.md#reporting-issues) FILE!!!**

Citra
==============
[![Travis CI Build Status](https://travis-ci.org/citra-emu/citra.svg?branch=master)](https://travis-ci.org/citra-emu/citra)
[![AppVeyor CI Build Status](https://ci.appveyor.com/api/projects/status/sdf1o4kh3g1e68m9?svg=true)](https://ci.appveyor.com/project/bunnei/citra)

Citra is an experimental open-source Nintendo 3DS emulator/debugger written in C++. It is written with portability in mind, with builds actively maintained for Windows, Linux and macOS.

Citra emulates a subset of 3DS hardware and therefore is useful for running/debugging homebrew applications, and it is also able to run many commercial games! Some of these do not run at a playable state, but we are working every day to advance the project forward. (Playable here means compatibility of at least "Okay" on our [game compatibility list](https://citra-emu.org/game).)

Citra is licensed under the GPLv2 (or any later version). Refer to the license.txt file included. Please read the [FAQ](https://citra-emu.org/wiki/faq/) before getting started with the project.

Check out our [website](https://citra-emu.org/)!

For development discussion, please join us at #citra-dev on freenode.

### Development

Most of the development happens on GitHub. It's also where [our central repository](https://github.com/citra-emu/citra) is hosted.

If you want to contribute please take a look at the [Contributor's Guide](CONTRIBUTING.md) and [Developer Information](https://github.com/citra-emu/citra/wiki/Developer-Information). You should as well contact any of the developers in the forum in order to know about the current state of the emulator because the [TODO list](https://docs.google.com/document/d/1SWIop0uBI9IW8VGg97TAtoT_CHNoP42FzYmvG1F4QDA) isn't maintained anymore.

If you want to contribute to the user interface translation, please checkout [citra project on transifex](https://www.transifex.com/citra/citra). We centralize the translation work there, and periodically upstream translation.

### Building

* __Windows__: [Windows Build](https://github.com/citra-emu/citra/wiki/Building-For-Windows)
* __Linux__: [Linux Build](https://github.com/citra-emu/citra/wiki/Building-For-Linux)
* __macOS__: [macOS Build](https://github.com/citra-emu/citra/wiki/Building-for-macOS)


### Support
We happily accept monetary donations or donated games and hardware. Please see our [donations page](https://citra-emu.org/donate/) for more information on how you can contribute to Citra. Any donations received will go towards things like:
* 3DS consoles for developers to explore the hardware
* 3DS games for testing
* Any equipment required for homebrew
* Infrastructure setup
* Eventually 3D displays to get proper 3D output working

We also more than gladly accept used 3DS consoles, preferably ones with firmware 4.5 or lower! If you would like to give yours away, don't hesitate to join our IRC channel #citra on [Freenode](http://webchat.freenode.net/?channels=citra) and talk to neobrain or bunnei. Mind you, IRC is slow-paced, so it might be a while until people reply. If you're in a hurry you can just leave contact details in the channel or via private message and we'll get back to you.
