# Media Files

This is a simple HTML page that demonstrates how to use audio and video tags to embed media files in a web page.

## Audio Files

The audio files are stored in the same folder as the HTML file, and have the names 1.mp3, 2.mp3, 3.mp3, 4.mp3, 5.mp3, and 6.mp3. They are played using the `<audio>` tag, which has the `controls` attribute to enable the user to play, pause, and adjust the volume of the audio. The `src` attribute specifies the source of the audio file, and the text inside the tag is displayed if the browser does not support the audio element.

The syntax for the audio tag is:

```html
<audio controls src="filename.mp3">Your browser does not support the audio element.</audio>
```

## Video Files

The video files are also stored in the same folder as the HTML file, and have the names 1.mp4, 2.mp4, 3.mp4, 4.mp4, 5.mp4, and 6.mp4. They are played using the `<video>` tag, which has the `controls` attribute to enable the user to play, pause, and adjust the volume of the video. The `src` attribute specifies the source of the video file, and the `width` and `height` attributes specify the dimensions of the video player. The text inside the tag is displayed if the browser does not support the video element.

The syntax for the video tag is:

```html
<video width="320" height="240" controls src="filename.mp4">Your browser does not support the video tag.</video>
```