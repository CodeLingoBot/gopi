
<table style="border-color: white;"><tr>
  <td width="50%">
    <img src="https://raw.githubusercontent.com/djthorpe/gopi/master/etc/images/gopi-800x388.png" alt="GOPI" style="width:200px">
  </td><td>
    Go Language Application Framework
  </td>
</tr></table>

This repository contains an application framework for the Go language, which
will allow you to develop applications which utilize a number of features
of your computer. It's targetted at the Raspberry Pi but maybe parts of it
would work on general Linux and Macintosh environments.

The following features are supported on various platforms:

  * The GPIO device, I2C and SPI interfaces
  * Display and display surfaces, bitmaps and vector graphics
  * GPU acceleration for 2D graphics
  * Font loading and rendering in bitmap and vector forms
  * Input devices like the mouse, keyboard and touchscreen
  * Infrared transmission and receiving, for example for remote controls

It would also be great to support the following features in the future:

  * Image and video encoding/decoding, including utilizing hardware
    acceleration
  * Connected cameras
  * 3D graphics

More information on usage is available at http://djthorpe.github.io/gopi/

# Requirements

The tested requirements are currently:

  * Any Raspberry Pi
  * Raspian Jessie Lite 4.4 (other distributions may work, but not tested
  * Go 1.9

In order to use the library, you'll need to have a working version of Go on 
your Raspberry Pi, which you can [download](https://golang.org/dl/). Then 
retrieve the library on your device, using:

```
go get github.com/djthorpe/gopi
```

# License

```
Copyright 2016-2018 David Thorpe All Rights Reserved

Redistribution and use in source and binary forms, with or without 
modification, are permitted with some conditions. 
```

This repository is released under the BSD License. Please see the file
[LICENSE](LICENSE.md) for a copy of this license and for a list of the
conditions for redistribution and use.
