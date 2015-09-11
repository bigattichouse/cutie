Cutie - headless Qt/webkit browser with a node.js interface
================================================================
Cutie is a headless webbrowser based on browserjet. Cutie adds
a more refined API on top of browserjet (https://github.com/briankircho/browserjet), as well as some additional logic to wait for page loads for more detailed introspection of your tested website.

Cutie abstracts the browser objects, events and evaluations away from the immediate code execution to better manage the session during cucumber tests.

Installing
--------------------------------------
Cutie/Browserjet's binary depends on [Qt4](https://www.qt.io/download-open-source/) and Qt-Webkit, therefore you will need it installed on your system for the build to succeed.
Only Linux 32/64 bits have been tested so far.

* Ubuntu: `apt-get install libqtwebkit-dev`

Building browserjet from inside cutie:
    cd cutie/
    qmake-qt4
    make
    

