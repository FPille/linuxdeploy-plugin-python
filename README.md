
# A Python plugin for linuxdeploy [![Build Status](https://travis-ci.com/niess/linuxdeploy-plugin-python.svg?branch=master)](https://travis-ci.com/niess/linuxdeploy-plugin-python)


## [For developers][WIKI_DEVS]

This is a plugin for [linuxdeploy][LINUXDEPLOY]. It helps building _lightweight_
[Python][PYTHON] based [AppImage][APPIMAGE] applications by bundling a
_minimalist_ source distribution of [Python][PYTHON] inside an [AppDir][APPDIR].
Extra site specific packages can be bundled as well using `pip`, E.g. binaries
from [PyPi][PYPI].  Specific instructions for building and configuring the image
are located on the [wiki][WIKI_DEVS].


## [For users][WIKI_USERS] 

Ready to use [AppImage][APPIMAGE] distributions of [Python][PYTHON] are provided
[below](##Downloads) or in the [release][RELEASE] area. A one liner example is:
```
wget -cq https://github.com/niess/linuxdeploy-plugin-python/releases/download/continuous/python3-$(arch).AppImage && chmod u+x python3-$(arch).AppImage && ./python3-$(arch).AppImage
```
which will install and run a [Python][PYTHON] instance.  See the instructions on
the [wiki][WIKI_USERS] for more detailed usage.

## Downloadable AppImages

[![Python 2](https://img.shields.io/badge/python2-x86_64-blue.svg)](https://github.com/niess/linuxdeploy-plugin-python/releases/download/continuous/python2-x86_64.AppImage)
[![Python 3](https://img.shields.io/badge/python3-x86_64-blue.svg)](https://github.com/niess/linuxdeploy-plugin-python/releases/download/continuous/python3-x86_64.AppImage)
[![Plugin](https://img.shields.io/badge/plugin-x86_64-blue.svg)](https://github.com/niess/linuxdeploy-plugin-python/releases/download/continuous/linuxdeploy-plugin-python-x86_64.AppImage)



[APPIMAGE]: https://appimage.org
[APPDIR]: https://docs.appimage.org/reference/appdir.html
[LINUXDEPLOY]: https://github.com/linuxdeploy/linuxdeploy
[PYPI]: https://pypi.org
[PYTHON]: https://www.python.org
[RELEASE]: https://github.com/niess/linuxdeploy-plugin-python/releases

[WIKI_DEVS]: ../../wiki/Developers
[WIKI_USERS]: ../../wiki/Users