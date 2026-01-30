# vis 2 implementation

This is the implementation of a visualization for iobroker using [vis2](https://github.com/ioBroker/ioBroker.vis-2) adapter.

## Dependencies

- [vis-2](https://github.com/ioBroker/ioBroker.vis-2)
- [vis-2-widgets-inventwo](https://github.com/inventwo/ioBroker.vis-2-widgets-inventwo)
- [vis-2-widgets-icontwo](https://github.com/inventwo/ioBroker.vis-2-widgets-icontwo)

## Structure

The structure in this repository is very similar to the structure of the iobroker object tree which is used. The root directory is structured according to the vis2-projects except `develop` project in vis2 which contains the develop-branch of this repository.

### main

The main vis implementation which is designed to be used on tablets and computer-browsers.

#### base

Contains the basic layout as well as other basic stuff.

#### building

The structur on this subdirectory is very similar to the structure in the object tree in iobroker.

#### detailmasks

Contains all masks that provides some details.

#### mainmasks

Contains all main masks which are part of the base layout.

#### outdoor

The structur on this subdirectory is very similar to the structure in the object tree in iobroker.

#### templates

Contains all templates for widgets and composite-widgets that are multiple used in this project.
