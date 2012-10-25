#Greyshade

Greyshade is a minimal theme for Octopress.
Based on [Slash](https://github.com/tommy351/Octopress-Theme-Slash)  

[Demo](http://shashankmehta.in/archive/2012/greyshade.html)

##Conditions

The only condition to use this theme for your octopress blog is that you have to set a different highlight color than the ones mentioned [here](https://github.com/shashankmehta/greyshade/wiki/Sites-using-Greyshade). When you have chosen a highlight color, please add it to the [wiki](https://github.com/shashankmehta/greyshade/wiki/Sites-using-Greyshade) so that no one else uses it.

##Install

Type the code below in terminal.

	$ git clone git@github.com:shashankmehta/greyshade.git .themes/greyshade
	$ echo "\$greyshade: color;" >> sass/custom/_colors.scss //Substitue 'color' with the color that you want as the highlight in the theme
	$ rake install['greyshade']
	$ rake generate

##License

MIT: [http://sm.mit-license.org](http://sm.mit-license.org/)