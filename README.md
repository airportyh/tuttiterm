Tuttiterm - Tutti for Your Terminal
===================================

Tuttiterm is a CLI interface in your terminal for Tutti - the multi-browser interactive Javascript shell.

Installation
------------

	npm install tuttiterm
	
Usage
-----

First, connect one or more browsers to a Tutti room. More information on [Tutti itself](http://tutti.tobyho.com).

	tuttiterm <tutti_room_url>
	
This should connect to the room and you'll get output like

	Welcome to Tutti - interactively run Javascript on multiple browsers!
	====================================================================
	You can execute any Javascript in the shell below.
	Logged in browsers: IE 9.0
	To connect another browser, just copy-n-paste the current URL into it.
	>
	
At this point, you can enter any Javascript and they will be executed on all browsers that are connected to the room. To exit type

	> exit
	


