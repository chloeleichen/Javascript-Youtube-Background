# Javascript-Youtube-Background
AKA TubeVideo

<strong>light-weight vannila javascript youtube backgroud maker (no need for jQuery or any other libraies, only 2KB minified), supports multiple video player instances on one page<strong>

Created by <a href="http://chloechen.io">Chloe Chen</a>

=====
<strong>Demo: <strong>
http://chloechen.io/tubeVideo/

Integrate or build upon it for free in your personal or commercial projects.

======
This is a light-weight vannila javascript youtube backgroud plug-in that allow you to create youtube background videos. The video will cover the entire container to which the object is created on. 

It supports multiple video player instances on one page, so you can have different video background for different regions! 

======
<strong>Usage: </strong>
It is super simpel to use: all it needs is the id of your Youtube video(<a href="https://www.youtube.com/watch?v=EKyirtVHsK0">here is a tutorial on how to find the ID for your yourtube video</a>)

<code>var el = document.getElementById("player");</code> <br>
<code>var player = new TubeVideo(el, {videoId: 'gxCaDMB6y18'});
</code>

======
<strong>Configurable <strong>

<code>ratio: 16 / 9,</code> <br>
<code>videoId: 'gxCaDMB6y18',</code> <br>
<code>mute: true,</code> <br>
<code>repeat: true,</code> <br>
<code>width: window.innerWidth,</code> <br>
<code>start: 0,</code> <br>
<code>modestbranding: 1,</code> <br>
<code>autoplay: 1,</code> <br>
<code>controls: 0,</code> <br>
<code>showinfo: 0,</code> <br>
<code>wmode: 'transparent',</code> <br>
<code>branding: 0,</code> <br>
<code>rel: 0,</code> <br>
<code>autohide: 0</code> <br>

=====

Inspired by jQuery tubular(http://www.seanmccambridge.com/tubular/) and jQuery.Youtubebackground (https://github.com/rochestb/jQuery.YoutubeBackground)
