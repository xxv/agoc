agoc
====

A simple Python command-line interface to AgoControl using the RPC interface.

Installation
------------

For now, this doesn't require anything outside the Python3 standard library.

Create an `~/.agoc.conf` file like so:

```
[server]
url=http://example.org:8008/jsonrpc
```

From there, you can use the names you assigned your devices to turn them
on/off/whatever:

```
agoc livingroom on
```

You can use any unique substring of a name too, though any non-alphanumeric
characters are ignored.

License
-------
Like AgoControl, this software is licensed under the GPLv3.

agoc - a simple cli for AgoControl  
Copyright (C) 2016  [Steve Pomeroy](https://staticfree.info/)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/).
