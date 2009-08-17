This is the Drupal 5.x version of this module.

In order to use this module you must FIRST install the Pear log package on your web server.
You may download this here :  http://pear.php.net/package/Log

On Debian Linux you can install the package as follows 
*  apt-get install php-log

Ubuntu and Fedora will surely have similar packages.

You also need to create your log directory, and set the permissions accordingly.
Again, on Debian Linux, this may be done as follows

* mkdir /var/log/drupal
* chown www-data.www-data /var/log/drupal 

Examples

log_debug("This message will recursively print out the contents of the node", $node);
log_error("If you've set your stacktrack level to ERROR or below, this message will come with a stacktrace");