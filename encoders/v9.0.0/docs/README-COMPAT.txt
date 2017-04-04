
                    Compatibility Notes for FreeBSD
                    -------------------------------

To ensure maximum back compatibility, the ionCube PHP Encoder for FreeBSD
is currently built on FreeBSD 6.2. This ensures that customers using older systems
can still enjoy the product.

The Encoder may not run on more recent FreeBSD systems without
the necessary compatibility support installed, but this can easily be added.

Where compatibility support is required, simply run the following command 
as root:

  pkg_add -r compat6x-i386

If you experience any problems running the Encoder software after adding
the compatibility support, please open a ticket at http://support.ioncube.com


Copyright (c) 2002-2015 ionCube Ltd.

