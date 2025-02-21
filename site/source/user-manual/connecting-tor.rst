.. _connecting-tor:

===================
Connecting Remotely
===================
You can connect to your server and installed services from anywhere in the world, privately and anonymously, by using their unique Tor (`.onion`) URLs.

It is not currently supported to access your server and its installed services using a VPN. This functionality is coming in the next major release of StartOS.

.. note:: It is normal for Tor connections to be slow or unreliable at times

Running Tor on Your Phone/Computer (Recommended)
------------------------------------------------

- :ref:`Linux <tor-linux>`
- :ref:`Mac <tor-mac>`
- :ref:`Windows <tor-windows>`
- :ref:`Android <tor-android>`
- :ref:`iOS <tor-ios>`

Using the Tor Browser
---------------------
Using the official Tor Browser allows you to access `.onion` URLs without additional configuration. However, accessing clearnet (`.com`, `.org`, ect) websites will also be routed over Tor, making them slower, and `.local` URLs cannot be accessed at all.

#. Linux, Mac, Windows, Android: `Download Tor Browser <https://torproject.org/download/>`_
#. iOS: lacks a well-functioning Tor Browser. We recommend following the guide above.
