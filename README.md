urlScheme
=========

Plugin for usage of url-schemes on Android.

Enables the app to be opened from no.tim.orderevent://?put=your&arguments=here.

When the app is invoked from an url, the url it was invoked with is passed as an argument to a function you need to put in index.html, like so:
<code>
		
	function handleOpenURL(invokationString) {
		//do something with the invokationString
	}
</code>
