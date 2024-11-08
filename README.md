# Config

This repository contains some available configs.

## Test Conditions

Latency test URL: https://telegram.org/

Only the available configs on the above test are present here.

## Install the requirements

- [Android](#android)
- [Windows](#windows)
- [Linux](#linux)

### => ***Android***

Download v2rayNG from here: https://github.com/2dust/v2rayNG/releases/latest

There are five types of releases:

- arm64-v8a
- armeabi-v7a
- universal
- x86
- x86-64

These releases refer to the CPU architecture of your phone. You can check your CPU architecture using apps like *Droid Hardware Info*.

- [Google Play](https://play.google.com/store/apps/details?id=com.inkwired.droidinfo&hl=en)
- [Soft98](https://soft98.ir/android/app-essential/196-droid-hardware-info.html)

> Lazy? just download the **universal** release.

### => ***Windows***

Download Nekoray from here: https://github.com/MatsuriDayo/nekoray/releases/latest

There are four types of releases:

- debian-x64
- linux-x64.AppImage
- linux64
- **windows64**

It's obvious which one you should download. After extracting the zip file, you don't need to install anything. Just run the app.

### => ***Linux***

Download Nekoray from here: https://github.com/MatsuriDayo/nekoray/releases/latest

## Use the configs

### Simpler method for *short* term

Open the [configs.txt](./config.txt) file and copy the contents. Now just paste the configs to the app.

However you should visit this file every time you need new configs.

### Simpler method for *long* term

> If you're on Android, you can't use this method.

### Windows

Download Git from here: https://git-scm.com/downloads/win

> > > > > >To-do

### Linux

Download and install git using the default pakage manager.

``` bash
git clone https://github.com/snaCW/Config.git && cd Config
```

Install `xclip` if not installed. Then just run the below command.

``` bash
xclip -selection clipboard < config.txt
```

Now all of the configs are copied into your clipboard. You can even use this `alias` to make it even simpler:

``` bash
alias cpc='xclip -selection clipboard < '
```

And then use this command:

``` bash
cpc config.txt
```
