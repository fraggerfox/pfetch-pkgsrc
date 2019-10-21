pfetch-pkgsrc
=============

NetBSD pkgsrc script for pfetch.

You can find pfetch [here][1]

NOTE: This package is not yet available in the pkgsrc tree.

Installation
------------

Copy `sysutils/pfetch` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/pkgsrc/sysutils/pfetch`<br>
`$ make install clean`

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above example.

Credits
-------

* pfetch is developed and maintained by [Dylan Araps][2]

License
-------

BSD 2-clause. See LICENSE.

[1]: https://github.com/dylanaraps/pfetch
[2]: https://github.com/dylanaraps
