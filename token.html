<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="robots" content="noindex,nofollow">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Live Player</title>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/clappr/latest/clappr.css">
   <script src="https://cdn.jsdelivr.net/clappr/latest/clappr.min.js"></script>


   <script type="text/javascript" src="https://cdn.jsdelivr.net/clappr.level-selector/latest/level-selector.min.js"></script>
   <script src="https://cdn.jsdelivr.net/npm/@clappr/hlsjs-playback@1.0.1/dist/hlsjs-playback.min.js"></script>

   <style type="text/css" media="screen" charset="utf-8">
        #live-player {
            position: fixed !important;
            position: absolute;
            top: 0;
            right: 0;
            bottom: 0;
            left: 0;
            background-color: black;
        }
        .dvr-player-wrapper {
            background-color: black;
        }
        [data-watermark] {
            min-width: 100px !important;
            max-width: 350px !important;
            width: 70% !important;
            top: 0px !important;
            right: -85px !important;
        }
    </style>
</head>
<body>
    <div id="live-player"></div>
    <script type="text/javascript">
        window.onload = function () {
            fetch('channels.json')
            .then(response => response.json())
            .then(channels => {
                const urlParams = new URLSearchParams(window.location.search);
                const channelName = urlParams.get('tv');
                const tvSource = channels[channelName];
                if (tvSource) {
                    var player = new Clappr.Player({
                        source: tvSource,
                        parentId: '#live-player',
                        width: '100%',
                        height: '100%',
                        autoPlayVisibleOnly: 'partial',
                        watermark: 'https://i.ibb.co/VMwb7DY/20231223-092825-0000.png',
                        position: 'top-right',
                        autoPlay: true,
 plugins: [HlsjsPlayback, LevelSelector],
                    });
                } else {
                    console.error("TV source not provided in the URL parameters or invalid channel name.");
                }
            })
            .catch(error => console.error('Error fetching channels:', error));
        }
    </script>
</body>
</html>