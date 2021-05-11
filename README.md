# Vimeo playback technology for for [Video.js](https://github.com/videojs/video.js)

## Install
You can use npm (`npm install videojs-vimeo`) or the source and build it using `npm run-script build`

## Example
```html
<!DOCTYPE html>
<html>
<head>
  <link type="text/css" rel="stylesheet" href="https://vjs.zencdn.net/7.11.4/video-js.css" />
</head>
<body>
  <video
    class="video-js vjs-default-skin vjs-big-play-centered"
    controls
    width="640" height="360"
    data-setup='{ "techOrder": ["Vimeo"], "sources": [{ "type": "video/vimeo", "src": "326701979"}], "vimeo": { "autoplay": false } }'
  >
  </video>

  <script src="https://vjs.zencdn.net/7.11.4/video.min.js"></script>
  <script src="dist/Vimeo.min.js"></script>
</body>
</html>
```