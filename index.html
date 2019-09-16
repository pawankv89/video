
<html>

<head>

<style>
</style>

</head>

<body>

     <h1>Tech Support</h1>
     <video id="video" width="640" height="480" autoplay></video>
	<button id="snap" >Snap Photo</button>
	<canvas id="canvas" width="640" height="480"></canvas>

<script type="text/javascript">

/* Reload Window Frame size when moving browser */

/* just javascript: */
  window.onload = function() {


			// Grab elements, create settings, etc.
            var canvas = document.getElementById('canvas');
            var context = canvas.getContext('2d');
            var video = document.getElementById('video');
            //var mediaConfig =  { video: true };
          //var mediaConfig =  { audio: true, video: { width: { min: 1024, ideal: 1280, max: 1920 }, height: { min: 776, ideal: 720, max: 1080 } } };

            var mediaConfig =  { audio: true, video: true };
            var errBack = function(e) {
            	console.log('An error has occurred!', e)
            };

			// Put video listeners into place
            if(navigator.mediaDevices && navigator.mediaDevices.getUserMedia) {
                navigator.mediaDevices.getUserMedia(mediaConfig).then(function(stream) {
					//video.src = window.URL.createObjectURL(stream);
					video.srcObject = stream;
                    video.play();
                });
            }

            /* Legacy code below! */
            else if(navigator.getUserMedia) { // Standard
				navigator.getUserMedia(mediaConfig, function(stream) {
					video.src = stream;
					video.play();
				}, errBack);
			} else if(navigator.webkitGetUserMedia) { // WebKit-prefixed
				navigator.webkitGetUserMedia(mediaConfig, function(stream){
					video.src = window.webkitURL.createObjectURL(stream);
					video.play();
				}, errBack);
			} else if(navigator.mozGetUserMedia) { // Mozilla-prefixed
				navigator.mozGetUserMedia(mediaConfig, function(stream){
					video.src = window.URL.createObjectURL(stream);
					video.play();
				}, errBack);
			}

			// Trigger photo take
			document.getElementById('snap').addEventListener('click', function() {
				context.drawImage(video, 0, 0, 640, 480);
        
        console.log("Buttton");
			});
		

 }
/* window.onresize = function(){ location.reload(); } */
/* with jquery: */
/* $(window).resize(function(){location.reload();});*/
/* Other */
/* $(window).on('resize',function(){location.reload();}); */

		// Put event listeners into place
		//window.addEventListener("DOMContentLoaded", function() {}, false);

	</script>

 </body>

</html>
		
