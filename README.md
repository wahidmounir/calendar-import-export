# iCal Import/Export

This app allows you to import iCalender files to your calender without using google synchronization services.

This is a updated fork from iCal Import/Export, found on Googlecode (http://code.google.com/p/ical-import-export/).

# Build with Gradle

1. Have Android SDK "tools", "platform-tools", and "build-tools" directories in your PATH (http://developer.android.com/sdk/index.html)
2. Open the Android SDK Manager (shell command: ``android``). Expand the Extras directory and install "Android Support Repository"
3. Export ANDROID_HOME pointing to your Android SDK
4. Download Android Support Repository, and Google Repository using Android SDK Manager
5. Execute ``./gradlew build``

# Contribute

Fork the git repository and do a Pull Request. I will merge your changes back into the main project.

# Libraries

All JAR-Libraries are provided in this repository under "libs".

# Coding Style

## Code
* Indentation: 4 spaces, no tabs
* Maximum line width for code and comments: 100
* Opening braces don't go on their own line
* Field names: Non-public, non-static fields start with m.
* Acronyms are words: Treat acronyms as words in names, yielding !XmlHttpRequest, getUrl(), etc.

See http://source.android.com/source/code-style.html

## XML
* XML Maximum line width 999
* XML: Split multiple attributes each on a new line (Eclipse: Properties -> XML -> XML Files -> Editor)
* XML: Indent using spaces with Indention size 4 (Eclipse: Properties -> XML -> XML Files -> Editor)

See http://www.androidpolice.com/2009/11/04/auto-formatting-android-xml-files-with-eclipse/

# Licenses
iCal Import/Export is licensed under the GPLv3+.
The file LICENSE includes the full license text.

## Details
iCal Import/Export is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

iCal Import/Export is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with iCal Import/Export.  If not, see <http://www.gnu.org/licenses/>.

## Libraries

* iCal4J
  https://github.com/ical4j
  New BSD License

* Apache Commons
  http://commons.apache.org
  Apache License v2

* backport-util-concurrent
  http://backport-jsr166.sourceforge.net
  Public Domain

## Images

* icon.svg
  Based on Tango Icon Library and RRZE Icon Set
  http://tango.freedesktop.org
  http://rrze-icon-set.berlios.de
  Public Domain (Tango Icon Library) and Creative Commons Attribution Share-Alike licence 3.0. (RRZE Icon Set)
