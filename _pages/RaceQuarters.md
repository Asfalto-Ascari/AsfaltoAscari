---
layout: quarters
title: Race Quarters
permalink: /RaceQuarters/
---

<div id="twitch-embed"></div>

<!-- Load the Twitch embed script -->
<script src="https://embed.twitch.tv/embed/v1.js"></script>

<!--
Create a Twitch.Embed object that will render
within the "twitch-embed" root element.
-->
<script type="text/javascript">
var embed = new Twitch.Embed("twitch-embed", {
width: "100%",
height: "100%",
channel: "asfaltoascari",
layout: "video",
autoplay: false,
// only needed if your site is also embedded on embed.example.com and othersite.example.com 
<!--parent: ["embed.example.com", "othersite.example.com"] -->
});

embed.addEventListener(Twitch.Embed.VIDEO_READY, () => {
var player = embed.getPlayer();
player.play();
});
</script>

<div style="background-image:url('http://corporate.asfaltoascari.com/Images/AsfaltoCorpBackground.png');background-size : cover; background-position: right bottom; width:1080px ;height :35vw">
	<div class ="option">
		<!--- !--->
	</div>
</div>

