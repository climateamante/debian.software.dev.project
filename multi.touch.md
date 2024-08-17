# Multi Touch


## Gestures

* Add user to input group
  - `sudo gpasswd -a $USER input`

* Touch Requirements:
  - `sudo apt-get install wmctrl python3 python3-setuptools xdotool python3-gi libinput-tools python3-gi`
  - `sudo apt install gnome-tweaks gnome-shell-extensions gnome-shell-extension-manager`
  - `sudo add-apt-repository ppa:touchegg/stable && sudo apt install touchegg`

* Extentions:
  - `x11 gestures`: change search from _popularity_ filter to __recent__


    
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


## Multitouch Testing and Calibration

### Finding Device ID and Testing Multi-Touch Capability
- **[CheckingMTDevice](https://wiki.ubuntu.com/Multitouch/Testing/CheckingMTDevice)**: How to find your device ID and test it for multi-touch capability.

### Using Geisview for Event Testing
- **[UsingGeisview](https://wiki.ubuntu.com/Multitouch/Testing/UsingGeisview)**: Using the geisview tool to see if you're getting expected events.

### Recording and Playback of Touch Events
- **[Evemu](https://wiki.ubuntu.com/Multitouch/Testing/Evemu)**: Recording and playback of touch events and gestures; extremely useful for debugging.

### Visual Feedback Tools
- **[UsingMtview](https://wiki.ubuntu.com/Multitouch/Testing/UsingMtview)**: A visual feedback tool that shows touch points, sizes, disconnects, offsets, etc.
- **[UsingUCube](https://wiki.ubuntu.com/Multitouch/Testing/UsingUCube)**: Another visual feedback tool, but instead of touch points checking, does gesture checking.

### Multitouch Support in Legacy Applications
- **[Ginn](https://wiki.ubuntu.com/Multitouch/Ginn)**: A tool to provide multitouch support in legacy applications without recoding; Ginn can be very helpful in testing an MT setup.

### Calibrating N-Trig Hardware
- **[Ntrig](https://wiki.ubuntu.com/Multitouch/Calibration/Ntrig)**: A tool for calibrating N-Trig hardware.
