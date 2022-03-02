# fluid.iframe
Iframe (fluid)
<script src="https://cdn.fluidplayer.com/v3/current/fluidplayer.min.js"></script>
<video id="video-id"><source src="video.mp4" type="video/mp4" />
<script>
    var myFP = fluidPlayer(
        'video-id',	{
	"layoutControls": {
		"controlBar": {
			"autoHideTimeout": 3,
			"animated": true,
			"autoHide": true
		},
		"htmlOnPauseBlock": {
			"html": null,
			"height": null,
			"width": null
		},
		"autoPlay": true,
		"mute": true,
		"allowTheatre": true,
		"playPauseAnimation": true,
		"playbackRateEnabled": false,
		"allowDownload": true,
		"playButtonShowing": true,
		"fillToContainer": true,
		"primaryColor": "#FF3399",
		"posterImage": "your-real-file-here.png"
	},
	"vastOptions": {
		"adList": [
			{
				"roll": "preRoll",
				"vastTag": "",
				"adText": ""
			}
		],
		"adCTAText": false,
		"adCTATextPosition": ""
	}
});
</script>
