TracGoogleAds
=============

TracGoogleAds_ is of course a trac_ plugin designed to display ads on your
trac_ environment.

The main feature of the plugin is that it allows the user to persistently_
hide the ads, making your trac_ environment less annoying to those who
dislike ads and supporting open-source projects through them.

Installation
------------
Installing the plugin is as easy as::

  sudo easy_install TracGoogleAds

And then enabling it:

.. sourcecode:: ini

  [components]
  tracext.google.ads.* = enabled

And that's it!

Now, all you have to do is to go to the administration and under **Google**
you have a **Ads** link to setup the plugin.

Bugs and/or New Features
------------------------

Please submit bugs of new features to::

  http://google.ufsoft.org/


Source Code
-----------

If you wish to be on the bleeding edge and get the latest available code:

.. sourcecode:: ini

  hg clone http://google.ufsoft.org/hg/ads-dev/ TracGoogleAds


**Note**: For up-to-date documentation please visit TracGoogleAds_'s site.

~~~~

.. [persistently] *The user choice of hiding the ads will remain untouched
                  throughout it's later visits, and he'll still have the
                  choice to display them again*.

.. _trac: http://trac.edgewall.org
.. _TracGoogleAds: http://google.ufsoft.org/wiki/TracGoogleAds
