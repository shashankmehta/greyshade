#Greyshade

Greyshade is a minimal, responsive theme for Octopress.
Starting point forked from [Slash](https://github.com/tommy351/Octopress-Theme-Slash)  

[Demo](http://shashankmehta.in/archive/2012/greyshade.html)

![mobile view](https://dl.dropbox.com/u/6396581/greyshade/1.png)

![Desktop view](https://dl.dropbox.com/u/6396581/greyshade/2.png)

##Features

1. Responsive design.
1. Fancybox integration
1. Gravatar support thanks to [Zhigang Fang](https://github.com/zhigang1992). Add your email id to `_config.yml` and your profile picture will appear in the left nav. 
1. [Schema.org](http://schema.org/) support thanks to [Nathan Shaughnessy](https://github.com/nathanshox)

##Conditions 

The only condition to use this theme for your octopress blog is that you have to set a different highlight color than the ones mentioned [here](https://github.com/shashankmehta/greyshade/wiki/Sites-using-Greyshade). When you have chosen a highlight color, please add it to the [wiki](https://github.com/shashankmehta/greyshade/wiki/Sites-using-Greyshade) so that no one else uses it.

Highlight color: This color is used on a:hover, blockquotes etc. I'll be using it in more places so that blogs with different highlight colors look slightly different and maintain a bit of their uniqueness. 

##Install

Assuming you have installed the default theme, type the code below in terminal.

    $ git clone git@github.com:shashankmehta/greyshade.git .themes/greyshade
    $ echo "\$greyshade: color;" >> sass/custom/_colors.scss //Substitue 'color' with your highlight color
    $ rake "install[greyshade]"
    $ rake generate

For profile picture and description, just add the relevant details in `_config.yml`
  
##License

MIT: [http://sm.mit-license.org](http://sm.mit-license.org/)
