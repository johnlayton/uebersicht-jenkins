# Übersicht Jenkins Widget

Made for [Übersicht](http://tracesof.net/uebersicht/)


## Options

You can find all options `index.coffee` at the top of the file:

1. Drag and drop the jenkins.widget folder in the Übersicht widgets folder

2. Set the configuration variables with your Jenkins data  
	user - your jenkins username  
	token - your jenkins access token (you can find it on http://{jekins URL}/user/{username}/configure)  
	serverUrlWithAuth - your jenkins server url when you have authentication, without http://
	serverUrlNoAuth  - your jenkins server url, with http://

3. Change your machine name in the function render  
	 machine = '{LukeSkywalker}'

## Appearance
To tweak the appearance, just change the css on the top of the index.coffee file.

![alt tag](http://brunopires.pt/Content/images/jenkins-widget.jpg)

#Version
version 0.6

## Credits
Original icons by Erik Flowers
http://erikflowers.github.io/weather-icons/
