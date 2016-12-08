
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no, minimum-scale=1, maximum-scale=1">
<meta name="apple-mobile-web-app-capable" content="yes">
<script type="text/javascript">
//<![CDATA[
try{if (!window.CloudFlare) {var CloudFlare=[{verbose:0,p:0,byc:0,owlid:"cf",bag2:1,mirage2:0,oracle:0,paths:{cloudflare:"/cdn-cgi/nexp/dok3v=1613a3a185/"},atok:"9a891dbccdd8388bae54ca67d90efd2e",petok:"63fcf4adb7a12e36c99d582a8bed58f7ca344040-1481240512-1800",zone:"matthewbauer.us",rocket:"0",apps:{"ga_key":{"ua":"UA-6667993-10","ga_bs":"2"}}}];!function(a,b){a=document.createElement("script"),b=document.getElementsByTagName("script")[0],a.async=!0,a.src="//ajax.cloudflare.com/cdn-cgi/nexp/dok3v=088620b277/cloudflare.min.js",b.parentNode.insertBefore(a,b)}()}}catch(e){};
//]]>
</script>
<link rel="stylesheet" href="index.css">
<title>gametime-player</title>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
  </script>
<script type="text/javascript">
/* <![CDATA[ */
var _gaq = _gaq || [];
_gaq.push(['_setAccount', 'UA-6667993-10']);
_gaq.push(['_trackPageview']);

(function() {
var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
})();

(function(b){(function(a){"__CF"in b&&"DJS"in b.__CF?b.__CF.DJS.push(a):"addEventListener"in b?b.addEventListener("load",a,!1):b.attachEvent("onload",a)})(function(){"FB"in b&&"Event"in FB&&"subscribe"in FB.Event&&(FB.Event.subscribe("edge.create",function(a){_gaq.push(["_trackSocial","facebook","like",a])}),FB.Event.subscribe("edge.remove",function(a){_gaq.push(["_trackSocial","facebook","unlike",a])}),FB.Event.subscribe("message.send",function(a){_gaq.push(["_trackSocial","facebook","send",a])}));"twttr"in b&&"events"in twttr&&"bind"in twttr.events&&twttr.events.bind("tweet",function(a){if(a){var b;if(a.target&&a.target.nodeName=="IFRAME")a:{if(a=a.target.src){a=a.split("#")[0].match(/[^?=&]+=([^&]*)?/g);b=0;for(var c;c=a[b];++b)if(c.indexOf("url")===0){b=unescape(c.split("=")[1]);break a}}b=void 0}_gaq.push(["_trackSocial","twitter","tweet",b])}})})})(window);
/* ]]> */
</script>
</head>
<body>
<div class="draghint hidden screen" id="draghint">
<input type="file" id="chooser" class="chooser"/>
<div class="dragtext">
<h1>drag a game here to play</h1>
</div>
</div>
<div id="loading" class="message screen"><h1>loading ...</h1></div>
<div id="error" class="message hidden screen">
<h1>error!</h1>
<p>quit and reopen to try again</p>
</div>
<div id="overlay" class="overlay"></div>
<div class="menu hidden screen" id="menu">
<input type="file" id="savechooser" class="chooser"/>
<div class="options">
<h1>Your game is paused.</h1>
<button id="resume" class="resume">resume</button>
<button id="reset" class="reset">reset</button>
<button id="save" class="save">save game</button>
<button id="load" class="load">load save</button>
<button id="mute" class="mute">mute</button>
</div>
<div>
<h1>Controls:</h1>
<div>A button = A key</div>
<div>B button = B key</div>
<div>X button = X key</div>
<div>Y button = Y key</div>
<div>L button = L key</div>
<div>R button = R key</div>
<div>D-pad = arrow keys</div>
</div>
<div>
<h1>Core Info:</h1>
<pre id="core-name"></pre>
<pre id="system-info"></pre>
<pre id="av-info"></pre>
</div>
</div>
<script src="jspm_packages/github/jmcriffey/bower-traceur-runtime@0.0.91/traceur-runtime.min.js"></script>
<script src="jspm_packages/system.js"></script>
<script src="config.js"></script>
<script src="build.js"></script>
<script>System.import('./index.coffee!')</script>
</body>
</html>
