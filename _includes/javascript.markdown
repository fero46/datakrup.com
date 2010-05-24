<script src="http://www.google.com/jsapi"></script>
<script>
google.load("jquery", "1");
</script>
<script src="/javascript/corner.js"></script>
<script src="/javascript/jquery.lavalamp.min.js" type="text/javascript" charset="utf-8"></script>
<script src="/javascript/jquery.easing.min.js" type="text/javascript" charset="utf-8"></script>
<!-- Include required JS files -->
<script type="text/javascript" src="/javascript/src/shCore.js"></script>
<!-- At least one brush, here we choose JS. You need to include a brush for every language you want to highlight -->
<script type="text/javascript" src="/javascript/scripts/shBrushRuby.js"></script>
<script type="text/javascript" src="/javascript/scripts/shBrushJava.js"></script>
<script type="text/javascript" src="/javascript/scripts/shBrushXML.js"></script>

<!-- Include *at least* the core style and default theme -->
<link href="/javascript/styles/shCore.css" rel="stylesheet" type="text/css" />
<link href="/javascript/styles/shThemeDefault.css" rel="stylesheet" type="text/css" />

<script type="text/javascript">
 //<![CDATA[
 (function() {
 	var links = document.getElementsByTagName('a');
 	var query = '?';
 	for(var i = 0; i < links.length; i++) {
 	if(links[i].href.indexOf('#disqus_thread') >= 0) {
 		query += 'url' + i + '=' + encodeURIComponent(links[i].href) + '&';
 	}
 	}
 	document.write('<script charset="utf-8" type="text/javascript" src="http://disqus.com/forums/system46/get_num_replies.js' + query + '"></' + 'script>');
 })();
 //]]>
 </script>

<script type="text/javascript" charset="utf-8">
$(document).ready(function(){
	$('#roundme').corner("15px");
	$('#footer').corner("15px bottom");
	SyntaxHighlighter.all();			
	$(function() { $(".lavaLamp").lavaLamp({ fx: "backout", speed: 700 })});
});
</script>