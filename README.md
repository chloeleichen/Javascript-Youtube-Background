# Javascript-Youtube-Background
AKA TubeVideo

light-weight vannila javascript youtube backgroud maker 

Created by Chloe Chen

http://chloechen.io

Integrate or build upon it for free in your personal or commercial projects.

======

This is a light-weight vannila javascript youtube backgroud plug-in that allow you to create youtube background videos. The video will cover the entire container to which the object is created on. 

======

Usage: 

var el = document.getElementById("player");
var player = new TubeVideo(el, {videoId: 'gxCaDMB6y18'});

======

Configurable 

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
