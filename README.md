# PyBrowser
a small web browser that is built entirely in Python. Uses `Qt5` for the windowing and the web engine.

**Currently in `Alpha` stage**

# some notes
* the PyBrowser uses `.json` files to save its settings and bookmarks. These files are saved to where the python script is located. **KEEP THIS IN MIND**

# the requirements
* a computer
* okay internet connection
* Python3, of course
* pip
* some patience

# the python dependencies
* PyQt5
* QtWebEngineWidgets
* sys

# getting it installed
You will need to first have python3 set up on your device. If it's installed already, make sure you are able to run the pip command.

If you're on Linux, then you can probably use your package manager to install the dependencies.
On Ubuntu, run `sudo apt install python3-pyqt5 python3-pyqt5.qtwebengine`

When you have the dependencies installed, you can finally execute the main python script using `python3 pybrowser.py` in the same folder as the python script.
