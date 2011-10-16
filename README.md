# README

This plug-in allows to add the [stackoverflow flair](http://stackoverflow.com/users/flair)  in the blog aside. 
It is useful for all developer that are proud of their contribution to this excellent platform and want to show
their ranking in the blog.

This plugin is quite simple. It consists of a simple modification in the  ___\_config.yml___ file and the addition of an aside html in the
asides section.

The configuration file must be modified by adding the stackoverflow.html aside in the list of default asides and providing the user name
and user id information (the user id is visible in the s.o. profile page url). If the user name is not specified the aside will not be
loaded.

The ___stackoverflow.html___ file must be placed in the default asides location:
/.themes/classic/source/\_includes/asides


