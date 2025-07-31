<!--
SPDX-FileCopyrightText: 2023-2025 Mirian Margiani
SPDX-License-Identifier: GFDL-1.3-or-later
-->

# SortFilterProxyModel

QML module for using Pierre-Yves Siret's
[SortFilterProxyModel](https://github.com/oKcerG/SortFilterProxyModel) in
Sailfish apps

This module provides an up-to-date and patched version of SortFilterProxyModel for QML (old Qt 5).


**To do:**

- [ ] properly include existing documentation
- [ ] import examples
- [ ] include in gallery
- [ ] release

This module is already in use in some apps: [Weather](https://github.com/ichthyosaurus/harbour-meteoswiss), and others


## Usage

```{qml}
import QtQuick 2.0
import Sailfish.Silica 1.0
import Opal.SortFilterProxyModel 1.0

MyComponent {
    // ...
}
```

## Screenshots

This is a purely technical module.

## How to use

You do not need to clone this repository if you only intend to use the module in
another project. Simply download the latest release bundle from the "Releases" page.

### Setup

Follow the main documentation for installing Opal modules
[here](https://github.com/Pretty-SFOS/opal/blob/main/README.md#using-opal).

### Configuration

See [`doc/gallery.qml`](doc/gallery.qml) for an example. Read the file to get
started.

### Documentation

Documentation is included in the release bundle and can be added to
QtCreator via Extras → Settings → Help → Documentation → Add.

## Translations

To **use** packaged translations in your project, follow the main documentation for
using Opal modules [here](https://github.com/Pretty-SFOS/opal#using-opal).

You can also **contribute** translations. If an app uses Opal modules, consider
updating its translations at the source (i.e. here), so that all Opal users can
benefit from it. Translations are managed using
[Weblate](https://hosted.weblate.org/projects/opal).

Please prefer Weblate over pull requests (which are still welcome, of course).
If you just found a minor problem, you can also
[leave a comment in the forum](https://forum.sailfishos.org/t/opal-qml-components-for-app-development/15801)
or [open an issue](https://github.com/Pretty-SFOS/opal/issues/new).

Please include the following details:

1. the language you were using
2. where you found the error
3. the incorrect text
4. the correct translation

See [the Qt documentation](https://doc.qt.io/qt-5/qml-qtqml-date.html#details) for
details on how to translate date formats to your local format.

## License

Packaged and adapted module:

    Copyright (C)  2025 Mirian Margiani
    Program: opal-sfpm

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

Original [SortFilterProxyModel](https://github.com/oKcerG/SortFilterProxyModel):

    The MIT License (MIT)
    Copyright (c) 2016 Pierre-Yves Siret

    Permission is hereby granted, free of charge, to any person obtaining a copy of
    this software and associated documentation files (the "Software"), to deal in
    the Software without restriction, including without limitation the rights to
    use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
    the Software, and to permit persons to whom the Software is furnished to do so,
    subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
    FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
    COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
    IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
    CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
