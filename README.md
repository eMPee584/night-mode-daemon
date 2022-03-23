# Night-mode Daemon
Simple automatic night-mode (blue light / red screen filter) for X11 implemented in Python, with a settings app (pyqt5).
Factored out from 
https://github.com/fsfw-dresden/usb-live-linux/tree/master/features/service_automatic_night_mode

## Requirements
```
python3-configobj       # config file reader and writer / "ini file round tripper
python3-daemon          # library for making a Unix daemon process
python3-pyqt5           # Python 3 bindings for Qt5
sct                     # set screen color temperature via xrandr - reduce or increase blue light
```

## FIXME
- no packaging as of yet, thus
- manual installation required
