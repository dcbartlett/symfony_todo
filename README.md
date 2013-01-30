Symfony ToDo
========================

Welcome to the Symfony ToDo - a ToDo app built on the extremely flexible
Symfony2 framework.

This document contains information on how to download, install, and start
using Symfony ToDo.

1) Installing the Symfony Todo
----------------------------------

When it comes to installing Symfony ToDo, you have a few options.

### Use Git (*recommended*)

Symfony ToDo can be downloaded with git.

    git clone git://github.com/dcbartlett/symfony_todo.git

This will get the project files.
You will still need to do the composer part.

### Download an Archive File

Symfony ToDo can also be downloaded as an [archive][1].

Just unpack it somewhere under your web server root directory.
You will still need to do the composer part.

### Use Composer to Finish Up

You also need to install all the necessary dependencies.
Download composer (see above) and run the

following command:

    cd /path/to/symfony_todo
    curl -s http://getcomposer.org/installer | php
    php composer.phar install

This will finish up and have the system ready to use.
You will now be able to point your webserver to this folder.

2) Checking your System Configuration
-------------------------------------

Execute the `check.php` script from the command line:

    php app/check.php

Access the `config.php` script from a browser:

    http://localhost/path/to/symfony/app/web/config.php

If you get any warnings or recommendations, fix them before moving on.

3) Done!
--------------------------------

Congratulations! You're now ready to use Symfony ToDo.

From the `config.php` page, click the "Bypass configuration and go to the
Welcome page" link to load up your first Symfony page.

You can also use a web-based configurator by clicking on the "Configure your
Symfony Application online" link of the `config.php` page.

Enjoy!

[1]:  http://symfony_todo.xancomp.com/download