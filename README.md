Filter Permissions
========
Filter Permissions enables you to filter the permission list by role and module 
to make it easier to find the permission you are looking for. It also allows
permissions to be saved if the site has a very large number of permissions.

Sites that have one or more of the following factors may struggle to save the
permissions form:
- a large number of modules that have permissions attached
- a large number of content types
- a large number of paragraph types and the Paragraphs Type Permissions
submodule is enabled
- a large number of roles

While there are some functions within Backdrop that try to mitigate this, on
some hosting it may not be possible to adjust (see the [documentation page](https://docs.backdropcms.org/max-input-vars))
and this module can enable saving of permissions, where it would not otherwise
be possible to save.

Filter Permissions does this by only saving the permissions in scope of the
filters. It will also provide a warning and hide the save button if the number
of permissions in scope means that it may not save.

If the number of permissions is not preventing saving but is causing the page
to take an excessive amount of time to load, then this module can also help
that by reducing the number being loaded on the page. 

From version 1.24.0, Backdrop includes a text based search filter that acts
instantly on the page to hide all non-matching permissions.  However, it does
not remove these permissions from the scope of the save and therefore if your
site is affected by the factors above, the text based search filter will be
hidden until you reduce the scope using Filter Permissions.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.


Issues
------

Bugs and Feature Requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/filter_perms/issues.


Current Maintainers
-------------------
- [Martin Price](https://github.com/yorkshire-pudding) - [System Horizons](https://www.systemhorizons.co.uk)
- Collaboration and co-maintainers welcome!

Credits
-------
- Ported to Backdrop CMS by - [Martin Price](https://github.com/yorkshire-pudding) - [System Horizons](https://www.systemhorizons.co.uk).
- Port sponsored by [System Horizons](https://www.systemhorizons.co.uk).
- Originally written for Drupal by [cYu](https://www.drupal.org/u/cyu).
- Maintained on Drupal by [cYu](https://www.drupal.org/u/cyu), 
[deeyaken](https://www.drupal.org/u/deekayen),
[ivagold](https://www.drupal.org/u/ivagold),
[mgbellaire](https://www.drupal.org/u/mgbellaire),
[willzyx](https://www.drupal.org/u/willzyx).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
