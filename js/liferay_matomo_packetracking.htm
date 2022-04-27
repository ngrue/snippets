<!-- Page tracking code for Matomo in Liferay -->
<!--
  Since Liferay 7.0, SPA is a great feature of Liferay. 
  But standard matomo tracking code does not work with it: unless you refresh 
  the page or deactivate senna, trackPageViews are never send after the 1st
  time. Solution consists of taking advantage of Liferay 'endNavigate' event.
  
  In the following code, replace the following items with their actual value:
  ITSME = user screenname (or erase the line if not needed
  BASE_URL = base url of matomo server
  matomo.php = matomo tracker (could be piwik.php)
  matomo.js = matomo js file (could be piwik.js)
-->
<script type="text/javascript">
/**
 * Copyright (c) 2022 Nicolas Grué, All rights reserved.
 *
 * This library is free software; you can redistribute it and/or modify it under
 * the terms of the GNU Lesser General Public License as published by the Free
 * Software Foundation; either version 2.1 of the License, or (at your option)
 * any later version.
 *
 * This library is distributed in the hope that it will be useful, but WITHOUT
 * ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
 * FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more
 * details.
 */
(!window.Matomo) && (function() {
	window._paq = window._paq || [];
	matomoEndNavigate = function() {
		_paq.push(['setCustomUrl', window.location.href]);
		_paq.push(['setDocumentTitle', document.title]);
		_paq.push(['trackPageView']);
	}
	Liferay.on('endNavigate', matomoEndNavigate);
	_paq.push(['setUserId', 'ITSME']);
	_paq.push(['enableLinkTracking']);
	var u="BASE_URL";
	_paq.push(['setTrackerUrl', u+'matomo.php']);
	_paq.push(['setSiteId', 'SITE_ID']);
	var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0];
	g.type='text/javascript'; g.async=true; g.defer=true; g.src=u+'matomo.js'; s.parentNode.insertBefore(g,s);

	matomoEndNavigate();
})();
</script>
<!-- END Page tracking code for Matomo in Liferay -->
