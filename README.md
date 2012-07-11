PyGame-Py3k-Script
==================

A Bash script that installs dependencies, downloads/converts/installs source code for PyGame to Py3k.

Instructions
------------
This build script is probably only valid for Ubuntu users using a recent release, say from 10.04 upwards (arbitrarily chosen).

Assuming you're using a compatible system, just download the script to the directory where you'd like PyGame's source code to be.
The script creates a folder for PyGame automatically, then downloads the source and converts/builds/installs to python 3 from there.

Naturally, python 3 is required, but this is addressed in the build script.

If you aren't using Ubuntu but your system uses the Apt package manager, try running the script. Debian Squeeze (the "stable" release) doesn't have Python3.2, so you'll have to install that yourself. Other dependencies may not be available except through backports repositories, or may have different names on your platform (for e.g., Ubuntu developer packages often end in "-dev", whereas some other platforms use "-devel").

At the very least, this script should serve as a sort of roadmap to resolving dependency-hell when trying to install and use PyGame on Python 3, at least until the PyGame devs get their act together and provide official support for modern Python.
