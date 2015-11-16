Podcats
=======

Podcats generates RSS feeds for podcast episodes from local audio files and,
optionally, exposes both the feed and episodes via a built in web server,
so that they can be imported into iTunes or another podcast client.


Installation
------------
::

    $ pip install podcats


Usage
-----

Generate a podcast RSS from audio files stored in `my/offline/podcasts`::

    $ podcats generate my/offline/podcasts


Generate & serve the feed as well as the files at http://localhost:5000. ::

    $ podcats serve my/offline/podcasts


For more options see ``podcats --help``.


Credit
-----

Forked from https://github.com/jkbrzt/podcats
