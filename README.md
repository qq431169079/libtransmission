Libtransmission
==========================

### Introduce

This is the BitTorrent C library used by [Transmission](http://www.transmissionbt.com/). 
Surely called 'libtransmission'

libtransmission is not introduced separately.

But it is really a good BT library, so I hack transmission's source code
and release it. 

All Rights reserved by Transmission


### Dependencies
Libtransmission depends on some third-party libraries,they are

		libdht
		libudp
		libminiupnp
		libnatpmp
		libevent
		libcurl
		libopenssl
		Posix Thread
		zlib

And some of them, libdht, libudp, libminiupnp, libnatpmp are included in
the repository, while others not.

### Compile
If you want to compile your code with libtransmission, do it like following
command:

		gcc code.c -L. -ltransmission -ldht -lutp -lminiupnp -lnatpmp -levent -lcurl -lssl -lcrypto -pthread -lz

Of course you can put your code in another directory,
   and you know how to link libtransmission and it's dependencies.

### Help
You may need some help to use libtransmission.

What a pity that libtransmission is not well documented, but you can help yourself and get help in IRC freenode #transmission channel too.

### Good Luck

