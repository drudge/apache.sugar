Apache.sugar for Espresso
=======================

Get the picture while reviewing apache configuration files using this sugar for the [Espresso text editor][espresso]. 

[espresso]: <http://macrabbit.com/espresso/> "The Espresso text editor, by MacRabbit"


Installation
------------
First install any and all dependencies, listed below. The instructions for
doing so can be found on their respective homes.

1. Clone this project somewhere, with the following:
    
    git clone git://github.com/conceited-drudge/apache.sugar.git ./Apache.sugar
    
2. Link it to your syntaxes directory:
    
    mkdir -p "~/Library/Application Support/Espresso/Sugars/"
    ln -s "$(pwd)/Apache.sugar" "/Users/$(whoami)/Library/Application Support/Espresso/Sugars/"
    
    
3. Close Espresso and reload, the sugar should be installed and functional.


Using
-----

Simply open a .htaccess, httpd.conf, apache2.conf, file or select the Apache syntax from the View->Language menu.

License
-------

The content in this sugar is public domain. A mention would be cool someplace if you do use it for anything cool though.


Credits
-------

Nicholas 'drudge' Penree <http://conceitedsoftware.com>