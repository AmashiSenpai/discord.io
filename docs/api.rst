.. currentmodule:: rpd

API Reference
=============
The full RPD API Reference.

Version Specific Details
------------------------
There is currently 2 ways to get version info

The easiest is via ``__version__``

.. data:: __version__

    A string representation of the version. e.g. ``'0.3.0'``. This is based
    off of :pep:`440`.

And second is by using ``version_info``

.. data:: version_info

    A named tuple that is similar to :obj:`py:sys.version_info`.

    Just like :obj:`py:sys.version_info` the valid values for ``releaselevel`` are
    'alpha', 'beta', 'candidate' and 'final'.


RESTClient
----------

.. attributetable:: internal.rest.RESTClient

.. autoclass:: internal.rest.RESTClient
    :members:


WebSockets
----------

.. autoclass:: internal.websockets.DiscordClientWebSocketResponse
    :members:

AioClient
---------

.. autoclass:: RESTClientResponse
    :members: