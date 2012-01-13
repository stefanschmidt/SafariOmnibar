Description
===========

This is a PowerPC port of Olivier Poitrey's Safari Omnibar which is a Safari SIMBL plugin aiming at mimicing the Chrome's smart location bar which combines location and search.

Requirements
============

- PowerPC
- Mac OS 10.5.8
- Safari 5.0.6
- [SIMBL 0.9.9](http://www.culater.net/software/SIMBL/SIMBL.php) or [PlugSuit 1.5.7](http://infinite-labs.net/plugsuit/)

Installation
============

1. Install either SIMBL or Plugsuit (the latter is recommended)
2. Download the current [release](https://github.com/stefanschmidt/SafariOmnibar/downloads)
3. Extract and copy SafariOmnibar.bundle to `~/Library/Application\ Support/SIMBL/Plugins`
4. Restart Safari

Uninstallation
==============

Remove the file `/Library/Application\ Support/SIMBL/Plugins/SafariOmnibar.bundle`

Usage
=====

Just type a search query in the location bar and it will perform a Google search.

TODO
====

- Preference Panel
- Let the user choose not to hide the Safari's search field
- Search engine editor with keyword support just like Chrome's
- Google auto-suggests injection in the completion menu
