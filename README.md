<!DOCTYPE html>
<html lang="en">
<head>

	<meta charset="utf-8">

	<title>Friday Night Funkin'</title>

	<meta id="viewport" name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
	<meta name="apple-mobile-web-app-capable" content="yes">	
	<script type="text/javascript" src="Funkin.js"></script>

	<script>
		window.addEventListener ("touchmove", function (event) { event.preventDefault (); }, { capture: false, passive: false });
		if (typeof window.devicePixelRatio !='undefined' && window.devicePixelRatio > 2) {
			var meta = document.getElementById ("viewport");
			meta.setAttribute ('content', 'width=device-width, initial-scale=' + (2 / window.devicePixelRatio) + ', user-scalable=no');
		}
	</script>

	<style>
		html,body { margin: 0; padding: 0; height: 100%; overflow: hidden; }
		#openfl-content { background: #000000; width: 100%; height: 100%; }
		@font-face {
			font-family: 'Pixel Arial 11 Bold';
			src: url('assets/fonts/pixel.eot?#iefix') format('embedded-opentype'),
			url('assets/fonts/pixel.woff') format('woff'),
			url('assets/fonts/pixel.otf') format('truetype');
			font-weight: normal;
			font-style: normal;
		}
		@font-face {
			font-family: 'VCR OSD Mono';
			src: url('assets/fonts/vcr.eot?#iefix') format('embedded-opentype'),
			url('assets/fonts/vcr.woff') format('woff'),
			url('assets/fonts/vcr.ttf') format('truetype'),
			url('assets/fonts/vcr.svg#VCR%20OSD%20Mono') format('svg');
			font-weight: normal;
			font-style: normal;
		}
		@font-face {
			font-family: 'Nokia Cellphone FC Small';
			src: url('flixel/fonts/nokiafc22.eot?#iefix') format('embedded-opentype'),
			url('flixel/fonts/nokiafc22.woff') format('woff'),
			url('flixel/fonts/nokiafc22.ttf') format('truetype'),
			url('flixel/fonts/nokiafc22.svg#Nokia%20Cellphone%20FC%20Small') format('svg');
			font-weight: normal;
			font-style: normal;
		}
		@font-face {
			font-family: 'Monsterrat';
			src: url('flixel/fonts/monsterrat.eot?#iefix') format('embedded-opentype'),
			url('flixel/fonts/monsterrat.woff') format('woff'),
			url('flixel/fonts/monsterrat.ttf') format('truetype'),
			url('flixel/fonts/monsterrat.svg#Monsterrat') format('svg');
			font-weight: normal;
			font-style: normal;
		}

	</style>

</head>
<body>

	<noscript>This webpage makes extensive use of JavaScript. Please enable JavaScript in your web browser to view this page.</noscript>

	<div id="openfl-content"></div>

	<script type="text/javascript">
		lime.embed ("Funkin", "openfl-content", 1280, 720, { parameters: {} });
	</script>

</body>
</html>
