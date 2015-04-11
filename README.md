# Javascript-Youtube-Background
AKA TubeVideo

<strong>light-weight vannila javascript youtube backgroud maker (no need for jQuery or any other libraies, only 2KB minified)<strong>

Created by <a href="http://chloechen.io">Chloe Chen</a>

=====
<strong>Demo: <strong>
http://chloechen.io/tubeVideo/

Integrate or build upon it for free in your personal or commercial projects.

======
This is a light-weight vannila javascript youtube backgroud plug-in that allow you to create youtube background videos. The video will cover the entire container to which the object is created on. 

======
<strong>Usage: </strong>
It is super simpel to use: all it needs is the id of your Youtube video(<a href="https://www.youtube.com/watch?v=EKyirtVHsK0">here is a tutorial on how to find the ID for your yourtube video</a>)

var el = document.getElementById("player");
var player = new TubeVideo(el, {videoId: 'gxCaDMB6y18'});

======
<strong>Configurable <strong>

ratio: 16 / 9,
videoId: 'gxCaDMB6y18',
mute: true,
repeat: true,
width: window.innerWidth,
start: 0,
modestbranding: 1,
autoplay: 1,
controls: 0,
showinfo: 0,
wmode: 'transparent',
branding: 0,
rel: 0,
autohide: 0

=====

Inspired by jQuery tubular(http://www.seanmccambridge.com/tubular/) and jQuery.Youtubebackground (https://github.com/rochestb/jQuery.YoutubeBackground)
