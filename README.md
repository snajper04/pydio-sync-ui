The pydio-sync repository is providing a headless python script for running the synchro. This project is communicating with Python through ZMQ to provide a systray-like UI for the sync service.
It's based on the Qt (see http://qt-project.org) library.

## Run

To run it, you must 
 * Install Qt and QtCreator
 * Make sure ZeroMQ in installed 
 * clone the project, 
 * init submodules, 
 * Open the .pro file inside Qt Creator and run the project from here.

Currently tested on Mac and Linux.

## Contributing

Please <a href="http://pyd.io/contribute/cla">sign the Contributor License Agreement</a> before contributing.
