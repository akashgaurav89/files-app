Files app for Papryos
=====================

[![GitHub release](https://img.shields.io/github/release/papyros/files-app.svg)](https://github.com/papyros/files-app)
[![Build Status](https://travis-ci.org/papyros/files-app.svg?branch=master)](https://travis-ci.org/papyros/files-app)
[![GitHub issues](https://img.shields.io/github/issues/papyros/files-app.svg)](https://github.com/papyros/files-app/issues)
[![Bountysource](https://img.shields.io/bountysource/team/papyros/activity.svg)](https://www.bountysource.com/teams/papyros)

This is the file manager app for Papyros. The UI is build with our [Material Design framework](https://github.com/papyros/qml-material), and the backend is based on the [Ubuntu Touch file manager](https://launchpad.net/ubuntu-filemanager-app). The goal is for the app to be cross patform and run on Linux, OS X, and Windows.

Brought to you by the [Papyros development team](https://github.com/papyros/files-app/graphs/contributors).

### Dependencies

 * Qt 5.3 or higher
 * [QML Material](https://github.com/papyros/qml-material)
 * [QML Extras](https://github.com/papyros/qml-extras)
 * [KI18n KDE framework](http://api.kde.org/frameworks-api/frameworks5-apidocs/ki18n/html/index.html) (used for translations)
 * [KDeclarative KDE framework](http://api.kde.org/frameworks-api/frameworks5-apidocs/kdeclarative/html/index.html) (used for translations in QML)

### Installation

From the root of the repository, run:

    $ mkdir build; cd build
    $ cmake ..
    $ make
    $ make check # Optional, make sure everything is working correctly
    $ sudo make install

### Licensing

QML Extras is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.
