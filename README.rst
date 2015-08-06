``django-tracking`` is a simple attempt at keeping track of visitors
to django-powered Web sites.  It also offers basic blacklisting
capabilities.

Authored by `Josh VanderLinden <http://www.codekoala.com//>`_, and some great
`contributors <https://github.com/codekoala/django-tracking/contributors>`_.

.. image:: https://img.shields.io/pypi/v/django-tracking.svg
    :target: https://pypi.python.org/pypi/django-tracking/

.. image:: https://img.shields.io/pypi/dm/django-tracking.svg
    :target: https://pypi.python.org/pypi/django-tracking/

.. image:: https://img.shields.io/github/license/bashu/django-tracking.svg
    :target: https://pypi.python.org/pypi/django-tracking/

.. image:: https://landscape.io/github/bashu/django-tracking/develop/landscape.svg?style=flat
    :target: https://landscape.io/github/bashu/django-tracking/develop

Features
--------

* Tracks the following information about your visitors:

  * Session key
  * IP address
  * User agent
  * Whether or not they are a registered user and logged in
  * Where they came from (HTTP-REFERER)
  * What page on your site they last visited
  * How many pages on your site they have visited

* Allows user-agent filtering for visitor tracking
* Automatic clean-up of old visitor records
* Can ban certain IP addresses, rendering the site useless to visitors from
  those IP's (great for stopping spam)
* The ability to have a live feed of active users on your website
* Template tags to:

  * display how many active users there are on your site
  * determine how many active users are on the same page within your site

