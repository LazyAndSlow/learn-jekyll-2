Jekyll will apply all of the configuration settings you specify in the defaults section of your _config.yml file.
 However, you can choose to override settings from other scope/values pair by specifying a more specific path for the scope.

You can see that in the second to last example above. First, we set the default layout to my-site. 
Then, using a more specific path, we set the default layout for files in the projects/ path to project. 
This can be done with any value that you would set in the page or post front matter.

Finally, if you set defaults in the site configuration by adding a defaults section to your _config.yml file, you can override those settings in a post or page file. 
All you need to do is specify the settings in the post or page front matter. 