Jasmine Spec Browser
=======================
A Sublime Text 3 plugin.
-------------------------

Shows a quick menu of all specs in the currently open Jasmine test spec suite. E.g. if the currently open file has:

    it('should do something or rather', function() {
        ...

    it('shouldn\'t do this or that', function() {
        ...


Then the quick menu will show:

- should do something or rather
- shouldn't do this or that


Selecting either of the specs in the list will scroll the corresponding test spec into view.

Commands
--------

- browse_jasmine_specs


Installation
------------

Copy the following files into a new folder "JasmineSpecBroser" inside your Sublime Packages directory:
- JasmineSpecBrowser.py
- Default.sublime-commands

**Note:** to locate your Sublime Packages directory, from within Sublime Text go to the Sublime Text menu -> Preferences -> Browse Packages.

