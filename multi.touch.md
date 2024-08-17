# Multi Touch


## Gestures

* Add user to input group
  - `sudo gpasswd -a $USER input`
  - `sudo apt-get install wmctrl python3 python3-setuptools xdotool python3-gi libinput-tools python3-gi`
* _Explanation_:
  - wmctrl: A command-line tool to interact with a Window Manager.
  - python3: The Python 3 interpreter.
  - python3-setuptools: Tools for building and installing Python packages.
  - xdotool: A tool for simulating keyboard input and mouse activity.
  - python3-gi: Python 3 bindings for gobject-introspection libraries.
  - libinput-tools: Tools for configuring and debugging libinput.
  - python3-gi: This package provides the GObject Introspection libraries for Python 3 (replacing python-gobject).

## Installs:

* Calibration:
  - `sudo apt install xinput-calibrator`
* Input:
  - `sudo snap install libinput`
 
## Debug:

* Mulit-Touch Test:
  - `sudo apt install evtest`
