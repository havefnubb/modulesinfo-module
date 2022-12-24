Modulesinfo module
==============

This is a module for Jelix, displaying list of modules installed into the 
application. It adds a menu item into the master_admin menu.

This module is for Jelix 1.7.2 and higher.

It was originally developped into the [Havefnubb project](https://github.com/havefnubb/havefnubb/).

Setting up the module
=====================

The best method is to use Composer.

In a commande line inside your project, execute:

```
composer require "havefnubb/modulesinfo-module"
```

Launch the configurator for your application to enable the module

```bash
php dev.php module:configure modulesinfo
```

After configuring the module, you should launch the installer of your application
to activate the module:

```bash
php install/installer.php
```

Go into the administration of your application, then into the rights
management. Enable the right "Access to modules informations" for users
or groups that are authorized to see these informations.

Corresponding users should see a menu item allowing to access to the list
of modules.
