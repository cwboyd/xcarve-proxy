# XCarve Proxy
A Node.js proxy server for connecting to a remote XCarve via a Raspberry Pi that is running [xcarve-server][1].
For detailed install instructions, please visit the tutorial on the [Adafruit Learning System][4].

## Installation

Make sure you have the latest stable version of [Node.js][3] installed on your computer.

```console
$ node -v
v7.0.0
```
Install `xcarve-proxy` on your computer using `npm`.

```console
$ npm install -g xcarve-proxy
```

## Starting the Proxy
Make sure you have [xcarve-server][1] running on your Raspberry Pi before continuing. If everything has
been setup properly, you can start the proxy daemon by running the following command:

```console
$ xcarve-proxy start

██╗  ██╗      ██████╗ █████╗ ██████╗ ██╗   ██╗███████╗
╚██╗██╔╝     ██╔════╝██╔══██╗██╔══██╗██║   ██║██╔════╝
 ╚███╔╝█████╗██║     ███████║██████╔╝██║   ██║█████╗
 ██╔██╗╚════╝██║     ██╔══██║██╔══██╗╚██╗ ██╔╝██╔══╝
██╔╝ ██╗     ╚██████╗██║  ██║██║  ██║ ╚████╔╝ ███████╗
╚═╝  ╚═╝      ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝  ╚══════╝

starting proxy on port 1338...
```

Visit [easel.inventables.com][2] to test the proxy.

## Stopping the Proxy

```console
$ xcarve-proxy stop
stopping proxy...
```
## License

Copyright (c) 2015-2016 Adafruit Industries. Licensed under the MIT license.

Adafruit invests time and resources providing this open source code,
please support Adafruit and open-source hardware by purchasing products
from [Adafruit](https://adafruit.com)!

[1]: https://github.com/adafruit/xcarve-server
[2]: http://easel.inventables.com
[3]: https://nodejs.org
[4]: https://learn.adafruit.com/control-an-xcarve-cnc-machine-wirelessly-with-a-raspberry-pi
