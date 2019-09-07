# Puppetcam

Export chrome tab as a video


1. Exported videos are stored in Downloads folder
2. Specify bitrate to control quality of the exported video by adjusting `videoBitsPerSecond` property in `background.js`


### Dependencies

1. npm modules listed in package.json

### Usage

```sh
npm install
node export.js http://tobiasahlin.com/spinkit/ spinner.webm 1280x720 10s
```


Thanks to [@cretz](https://github.com/cretz) for helping with automatic tab selection and avoiding the permission dialog

#### Motivation

Was looking for a method to use CSS+JS as motion design tools.
So on needed a proper way to export browser view as a video file.

#### Sample video
[![Puppetcam](https://img.youtube.com/vi/f7Vdd0ExWiY/0.jpg)](https://www.youtube.com/watch?v=f7Vdd0ExWiY "Puppetcam")

#### Changelog

- Change Puppeteer version to 1.7
- Add size and length parameter
- Fix size parameter (setViewport, deviceScaleFactor)
