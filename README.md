# LinuxToWinSample
[![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/dwyl/esta)<br/>

This is an example VSCode project to facilitate C++ builds on Linux to Windows and 'emulation' with Wine.<br/>
The tasks can be seen on the Command Pallete with Ctrl + Shift + P

Requires
```console
sudo apt-get install mingw-w64
sudo apt-get install wine
```

if your package installation process was different, make sure the compiler path
still matches on [tasks.json](.vscode/tasks.json)
