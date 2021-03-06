**NOTE:** PixelWeb is no longer actively supported as we dropped support in [BiblioPixel](http://github.com/maniacallabs/BiblioPixel) starting with BiblioPixel v3.0. Simply not enough users showed interest PixelWeb, so when making the v2.x to v3.0 transition for BiblioPixel it was decided to not worry about maintaining compatibility. However, you can still use PixelWeb with Python 2.7 by following the instructions below.

PixelWeb is a dynamic graphical interface for our super flexible animation SDK, [BiblioPixel](http://github.com/maniacallabs/BiblioPixel). It runs everywhere BiblioPixel does and provides an easy to use web-based interface to nearly everything BiblioPixel can do. This not only allows local system control but via any other computer on the same network<sup>&dagger;</sup>.  

## Installation

*Note: Manual install is possible but using pip is highly recommended and all that will be covered in the documentation. Also, Windows users should exclude "sudo" from all commands.

PixelWeb Requires Python 2.7 and is not compatbile with Python 3.x. If you do not have Python installed or are unsure, visit [python.org/downloads](http://python.org/downloads) and follow the instructions.*

Installing PixelWeb is easy:
```
sudo pip install PixelWeb
```

Once the install is complete run the following command:
```
sudo run-pixelweb
```
On every run, PixelWeb will automatically check if the system has the required dependencies and install them. This includes [BiblioPixelAnimations](http://github.com/maniacallabs/BiblioPixelAnimations), our animation repository. It contains the initial animations that will be available through the interface. Please see the Wiki on how to add your own animations.


<sup>&dagger;</sup> Note that PixelWeb is designed to be used like a desktop application by a single user at a time, despite being accessible from multiple systems at once. There is currently no mechanism to keep multiple interface instances in sync.
