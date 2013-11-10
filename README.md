Wallpapers
==========

Wallpapers for the Hawaii desktop environment.

## Dependencies

No build dependency for this module.

## Build

Building this module is a piece of cake.

Assuming you are in the source directory, just create a build directory
and run cmake:

```sh
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX=/opt/hawaii ..
```

If not passed, the `CMAKE_INSTALL_PREFIX` parameter defaults to /usr/local.
You have to specify a path that fits your needs, /opt/hawaii is just an example.

Package maintainers would pass `-DCMAKE_INSTALL_PREFIX=/usr`.

## Installation

It's really easy, it's just a matter of typing:

```sh
make install
```

from the build directory.
