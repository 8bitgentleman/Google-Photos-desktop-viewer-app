# Google-Play-Books-desktop-viewer-app
Google Play Books desktop viewer app for OS X.

It uses Electron.

[You can download the app right now](https://github.com/8bitgentleman/Google-Play-Books-desktop-viewer-app/releases).

This is an stop-gap measure untill I have a custom desktop app from scratch.

# Developments

## Requirements

- Node >= 4

### For Windows build on non-Windows platform

- Wine

Setting a custom icon requires it.
The reason is [here](https://github.com/maxogden/electron-packager#building-windows-apps-from-non-windows-platforms).

## Setup

```bash
npm i
```

## Usage

### Start

```bash
npm start # execute temporalilly
```

### Build

```bash
npm run archive # create *.app and *.exe, and the installer, and the zip archive
```

### Commands

```bash
npm run # show help
```
