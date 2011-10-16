# README

This plug-in allows to add the [stackoverflow flair](http://stackoverflow.com/users/flair)  in the blog aside. 
It is useful for all developer that are proud of their contribution to this excellent platform and want to show
their ranking in the blog.

This plugin is quite simple. It consists of a simple modification in the  __\_config.yml__ file and the addition of an aside html in the
asides section.

The configuration file must be modified by adding the stackoverflow.html aside in the list of default asides and providing the user name
and user id information (the user id is visible in the s.o. profile page url). If the user name is not specified the aside will not be
loaded.

The __stackoverflow.html__ file must be placed in the default asides location:
/.themes/classic/source/\_includes/asides

## INSTALLATION SCRIPT

Not available at the moment. Octopress main repo developers are investingating for a common way to manage plugins. At the moment we wait for specs to be defined before
creating the installer for this simple plugin.

## LINKS

[Octopress 3rd party plugins](https://github.com/imathis/octopress/wiki/3rd-party-plug-ins)
