# Technology Radar

A simple technology radar map (made famous by [Thoughtworks](http://www.thoughtworks.com/radar)).

### Add user info

Edit ``user.json``. This is displayed in the header showing your Gravatar and your name with a link to Twitter. You can also specify your custom header image. Try a nice one from [Unsplash](http://unsplash.com).

	{ "user":
	    [
	        {
	            "name": "",
	            "email": "",
	            "website": "",
	            "background": ""
	        }
	    ]
	}

### Add blips

Edit ``blips.json`` like this. Areas: techniques, tools, frameworks, platforms. Statuses: hold, assess, trial, adopt.

	{ "blips":
	    [
	        {
	            "title": "Node.js",
	            "area": "platforms",
	            "status": "trial",
	            "link": "http://nodejs.org"
	        },



### License
Copyright (c) 2014 Urban Sanden. Licensed under the MIT license.
