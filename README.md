# Introduction

Vscode extension packs for weex development.

## weex-new-project

This VS Code extension adds support for weex new project.

1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex new project
3. Enter

## weex platform add android project

1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex platform add android project
3. Enter

## weex platform add iOS project

1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex platform add iOS project
3. Enter

## weex-lang

vscode weex language support

[vscode-weex-lang](https://github.com/weex-cli/vscode-weex-lang)

## weex-doctor

This VS Code extension adds support status for weex devlopment environment.

1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex new project
3. Enter

## weex-debugger
Help launch weex-debugger debug weex.

1. cmd + shift + p (Windows: ctrl + shift + p)
2. Input weex debug
3. Enter

More info
see https://github.com/weexteam/weex-debugger

## weex-run

Run weex in Browser、IOS、Android

### 1. Open Project
Open a weex project create by `weex-new-project` or `weexToolkit`

### 2. Run

#### Run web

![](https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/run.web.gif)

#### Run IOS

![](https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/run.ios.gif)

#### Run Android

![](https://raw.githubusercontent.com/weex-cli/vscode-weex/master/asset/run.ios.gif)

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