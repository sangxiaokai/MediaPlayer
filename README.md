A Media Player Using the qml-material Library
=============================================

Still under development. Helped needed to find a great name for it!

### Dependencies

* Qt 5.6 or higher
* [qml-material](https://github.com/papyros/qml-material)
* [taglib](https://taglib.github.io/)
* [libffmpegthumbnailer](https://github.com/dirkvdb/ffmpegthumbnailer)

### Installation

Run from the root of the repository:

```sh
$ mkdir build
$ cd build
$ qmake ..
$ make
$ sudo make install
```

Then you should repeat the same steps in the folder of each plugin in order to install them. Without them, the application won't be as interesting.

Note: if qmake fails (or make, because of it), try using qmake-qt5 instead.

### Licensing

This is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser Public License as published by the Free Software Foundation; either version 2.1 of the License, or (at your option) any later version.
