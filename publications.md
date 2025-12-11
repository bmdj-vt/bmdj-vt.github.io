---
layout: full_header
title: Publications 
---

Up to date publications and research outputs can be found on Dr. David-John's [Google Scholar page](https://scholar.google.com/citations?user=YFxRRDUAAAAJ&hl=en&oi=ao)

Below is courtesy of [csauthors.net](https://www.csauthors.net/brendan-david-john/)

<!-- This div is a placeholder which will contain the publications -->
<div id="pubszone">
  Loading publications...
</div>
<!-- Function which will handle the content received through JSONP -->
<script type='text/javascript'>
//<![CDATA[
    function mycallback(ad_content) {
    	document.getElementById('pubszone').innerHTML = ad_content.html;
    }
//]]>
</script>
<!-- Load of the remote JS which will call the callback function -->
<script src="https://www.csauthors.net/brendan-david-john/embed/bib.js?callback=mycallback"></script>