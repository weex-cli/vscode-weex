# Introduction

Vscode extension packs for weex development.
Use it to do the following things:

* Create new weex project ([weex-new-project](#weex-new-project))
* Add weex IOS and Android project ([weex-new-project](#weex-new-project))
* Weex language support for vscode ([weex-lang](#weex-lang))
* Check weex IOS and Android devlopment environment ([weex-doctor](#weex-doctor))
* Launch weex-debugger debug weex ([weex-debugger](#weex-debugger))
* Run weex in Web,IOS,Android ([weex-run](#weex-run))

# Install

In vscode extensions marketplace search `vscode-weex`, install the first.

# Included extensions

## weex-new-project

This VS Code extension adds support for weex new project.

### Use

1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex new project
3. Enter

### Demo
<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/new.project.gif" max-width="1000">

## weex platform add android project

### Use
1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex platform add android project
3. Enter

### Demo
<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/new.android.gif" max-width="1000">



## weex platform add iOS project

### Use
1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex platform add iOS project
3. Enter

## weex-lang

vscode weex language support

More info: [vscode-weex-lang](https://github.com/weex-cli/vscode-weex-lang)

### Demo
<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/weex.lang.gif" max-width="1000">

## weex-doctor

This VS Code extension is testing the weex development environment

### Use
1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex doctor
3. Enter

### Demo
<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/weex.doctor.gif" max-width="1000">

## weex-debugger
Help launch weex-debugger debug weex.

### Use
1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex debug
3. Enter

More info
see https://github.com/weexteam/weex-debugger

## weex-run

Run weex in Web,IOS,Android

### Use

#### 1. Open Project

Open a weex project create by `weex-new-project` or `weexToolkit`

#### 2. Run

Run web

<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/run.web.gif" max-width="1000">


Run IOS

<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/run.ios.gif" max-width="1000">

Run IOS result

<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/run.ios.result.gif" max-width="1000">

Run Android

<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/run.android.gif" max-width="1000">

Run Android result

<img src="https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/run.android.result.gif" max-width="1000">

### 3. Config launch.json

The launch.json path is `.vscode/launch.json`, you can edit it to config runner.

### Note

* Run IOS or Android APP make sure you have added native project (Path of which you `launch.json` key `projectPath` set), you can use )[weex-new-project](#weex-platform-add-android-project) add native project

* If the run fails, You can try to check the environment by [weex-doctor](#weex-doctor)

* IOS Environmental dependence: `xcode` and open once

* Android Environmental dependence: `Android studio`, `Java SDK 1.8` (Windows need set Java home https://developer.android.com/studio/install?hl=zh-cn), `Android SDK Platform 26` (Install by Android studio), `Android SDK Build-Tools 26` (Install by Android studio), `Android virtual device` (Install by Android studio)

* Debugging in the vscode editor breakpoint is not yet supported

# Issues

https://github.com/weex-cli/vscode-weex/issues