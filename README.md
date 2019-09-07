# html2screen

html2screen export html animation to video file.

### Usage

```sh
npm install
node export.js http://tobiasahlin.com/spinkit/ spinner.webm 1280x720 10s
```

1. html2screen require npm modules listed in package.json
2. Exported videos are stored in Downloads folder
3. Specify bitrate to control quality of the exported video by adjusting `videoBitsPerSecond` property in `background.js`

### Motivation

It's mean to use HTML+CSS+JS as motion designer tools.

It's inspired by [html2print](http://osp.kitchen/tools/html2print/) philosophy.

It's based on [https://github.com/GoogleChrome/puppeteer](Puppeteer) and [https://github.com/muralikg/puppetcam](Puppetcam).

#### Sample video
[![html2screen](https://img.youtube.com/vi/JM1Zw9oXSGI/0.jpg)](https://youtu.be/JM1Zw9oXSGI)

#### Changelog

- Change Puppeteer version to 1.7
- Add size and length parameter
- Fix size parameter (setViewport, deviceScaleFactor)
